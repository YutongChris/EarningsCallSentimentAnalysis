# EarningsCallSentimentAnalysis
This project implements a NLP pipeline to quantify sentiment from quarterly earnings call transcripts and correlate it with short-term stock price movements. 

Working Pipline: 

collect earnings call transcripts (select sentences) + collect stocks'5 days closed prices after earnings calls
                                                      |
                                                merge the data
                                                       |
                                                DualModalCrossAttn
