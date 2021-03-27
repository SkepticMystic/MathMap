#statistics 
# Median
---
The _median_ of a sample is the value which lies in the middle **after** sorting the sample in **ascending order**.

We can think of this as the "_middle_" value.

The formula we use to calculate the median value tells us the _position_ of the median, **not the value itself**.

$$Position~of~Median~=~\frac{n~+~1}{2}$$

Where:

- $n~=~Sample~Size$

We then use that position to find the value of the median from the sorted sample.

The exact steps will differ based on how many values we have in the sample.

## Example

### Odd sample size

If we have a dataset of 5 values:

$$\{3,~7,~1,~5,~4\}$$

We first sort the sample in ascending order:

$$\{1,~3,~4,~5,~7\}$$

The, use the formula to find the _position_ of the median value:

$Position~=~\frac{5~+~1}{2}~=~3^{rd}~Position$

Now we find the value in the $3^{rd}$ position which is our median!

$Median~=~$ {1, 3, ==4==, 5, 7} $~~=~4$

### Even sample size

This process is slightly different we we have an even number of values.

Suppose we ask 6 people how old they are and get the following dataset:

| Person | Age |
|:------:|:---:|
|   1    | 26  |
|   2    | 38  |
|   3    | 29  |
|   4    | 47  |
|   5    | 18  |
|   6    | 33  |

Now, to find the median value, we first sort the data in ascending order:

$$\{18,~26,~29,~33,~28,~47\}$$

Next, we use the formula to find the _position_ of the median:

$$Position~=~\frac{6~+~1}{2}~=~3.5^{th}~Position$$

But how can we take the three-and-a-halfth position? We do this by taking the mean of the value just before, and the value just after. In this case, we take the $3^{rd}$ and $4^{th}$ values, and calculate their mean:

$3^{rd}~Value~=~29$
$4^{th}~Value~=~33$

$\therefore~~3.5^{th}~Value~=~\frac{29~+~33}{2}~=~31$

This makes sense, right? 31 _is_ between 29 and 33, so it feels right that this is the median.