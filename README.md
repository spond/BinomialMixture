BinomialMixture
===============

Binomial Mixture Fitting using EM with restarts

Try 

`
cat data/test.txt | /path/to/BinMix
`

to get the following JSON output 

`
{
"1" : {
"Log-L":-191449.6814,
"c-AIC":382901.3709,
"rates" : [ 0.4175472645],
"weights": [ 1]
}
,
"2" : {
"Log-L":-2497.453234,
"c-AIC":5000.954854,
"rates" : [ 0.2995138457,0.9000679855],
"weights": [ 0.804,0.196]
}
}
`

The data were simulated with rates 0.3 (w=0.8) and 0.9 (w=0.2) 
