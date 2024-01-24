# SussySort 

![](https://github.com/DanielMartinecCZ/SussySort/blob/main/sus.png)


## How does it work?

1. While the list is not sorted and its length is greater than 0, a random passenger (SUS) is selected.
2. The other passengers then vote on whether SUS is really a imposter or just a crewmate.
3. If more than a half of the passengers think he is an impostor, he is ejected.
4. This process continues until the list is sorted or only one passenger remains.

- This means that list is always altered randomly and output is not predictable
- This also means that if the list is not ordered, there will always be some elements missing at the end of "sorting"
- The more ordered the list is, the faster it is sorted


## Code example

```python
from sussysort_alg.sussysort import sussy_sort

my_list = [1,8,7,6,5,6,7,1]
sussy_sort(my_list)

```

## Importing

- You can import SussySort to your program as pip package:
[Pip package](https://pypi.org/project/sussysort-alg/)

