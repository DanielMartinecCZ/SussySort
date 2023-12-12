# SussySort 

![](https://private-user-images.githubusercontent.com/92686959/289876247-44f375e6-b252-45be-8cf2-0cf81da3975a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDIzODg2MDMsIm5iZiI6MTcwMjM4ODMwMywicGF0aCI6Ii85MjY4Njk1OS8yODk4NzYyNDctNDRmMzc1ZTYtYjI1Mi00NWJlLThjZjItMGNmODFkYTM5NzVhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjEyVDEzMzgyM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBkOWY3NDdkZGFkOTY0YjcxNjk3ZDNiNmY3ZjhmZTQ0YWM3MDVkMTkzMTU2NjA0MTllOTdhMGZiZmM1NDJlZDAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.rXIoz3mu97T2Gm8MK0h_ZnK5Mg4VGVuD3wZegZCPqGw)


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

