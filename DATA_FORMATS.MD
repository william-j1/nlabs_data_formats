# Data Formats

NLABS.app encompasses many object types and each has its own format for data exchange.

# Object Types

| Object     | Serial Format                         | Sample                          |
|:----------:|---------------------------------------|---------------------------------|
| Histogram  | Min:Max:Bins:X_Label:Y_Label:x1,x2,x3 | Histogram:1:2:3:eA==:eQ==:1,2,1 |
| Image      | Constant:Width:Height:R,G,B,A,R..     | Image:100:100:102,53,88,255,43  |
| Linegraph  | X_Label:Y_Label:y1,y2,y3,y4,y6,y7     | Linegraph:eA==:eQ==:0,2,1.76,6  |
| Scatter	 | X_Label:Y_Label:x1,y1,x2,y2,x3,y3     | Scatter:eA==:eQ==:2,3,6,1,1.7,5 |

# Encoding

| Object  | Type    |
|:-------:|---------|
| X_Label | base 64 |
| Y_Label | base 64 |
