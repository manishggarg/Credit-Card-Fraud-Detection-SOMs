# Credit Card Fraud Detection Using SOMs
1. Self organizing Maps (SOMs) are most well-known, unsupervised approach ofneural network that is used for clustering and are very efficient in handling
large and high dimensional dataset.
1. SOMs can be applied on large complexset, so it can be implemented to detect credit card fraud.
1. we apply the Self-Organizing Map algorithm to create a model of typical cardholder's behavior and to analyze the deviation of transactions, thus finding suspicious transactions
## The attributes of this dataset(*Credit_Card_Applications.csv*) are:
- `CustomerID` – Id of the customer 
- `A1` – categorical, possible values: 0 and 1
- `A2` – continuous
- `A3` – continuous
- `A4` – categorical, possible values: 1, 2 and 3
- `A5` – categorical, possible values: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14
- `A6` – categorical, possible values: 1, 2, 3, 4, 5, 6, 7, 8, 9
- `A7` – continuous
- `A8` – categorical, possible values: 0 and 1
- `A9` – categorical, possible values: 0 and 1
- `A10`– continuous
- `A11` – categorical, possible values: 0 and 1
- `A12` – categorical, possible values: 1, 2 and 3
- `A13` – continuous
- `A14` – continuous
- `A15` (Class) – class attribute, possible values: 1 and 2
## Steps:
1. To implement SOMs first you need to import `MiniSom` class from module `minisom`. 
1. you can install it via command `pip install MiniSom` or download `minisom.py`. 
1. In other part you can make a analysis the credit card transaction by using ML/DL you can download the data from here [creditcard.csv](https://drive.google.com/open?id=1geJaybKU_bjTXnEOjhnXtqEswwHPrjU6)

**Distance between two neuron in SOMs** =<br/>
<pre>
              Jx(p)=minj││X-Wj(p)││={ Xi-Wij(p)]^2}^1/2
              </pre>
              
Where j=1, 2……m <br/>
W is neuron or weight matrix,<br/>
X is Input vector<br/>
The main output of SOM is the patterns and cluster it has given as output vector
