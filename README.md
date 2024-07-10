# My implementation of K-means clustering and E-M expectation
This is my implementation of K-means Clustering and E-M expectation. <br>
<br>
**1. K-means clustering** <br>
With different number of neighbors, costs and all images corresponding to each number of neighrs are displayed to show how the image of quality becomes better with higher number of neighbors. 

| Original | `<K = 2>` | `<K = 4>` | `<K = 8>` |
|--------------|----------------|-----------------|-----------------|
| ![Original](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/d3846632-aa29-4bca-a47c-f0afb42f896b) | ![K=2](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/48305fc3-79de-4a42-aa3c-5b3bf46fb4bd) | ![K=4](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/a227b405-3cf2-4cd2-9e0a-37f238526605) | ![K=8](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/aa6d289d-3c2f-4529-b5d5-9596581fa4f1) |
| **Original** | **`<Loss: 21.4>`** | **`<Loss: 12.7>`** | **`<Loss: 8.73>`** |


**2. E-M expectation clustering** <br>
E-M expection finds out the best clusters that express the images, given the certain number of clusters. We use E-step to calculate the information of each cluster and M-step to update every parameter. All the information includes means, variances, and mixing probabilities. Instead of displaying them all, I only show images to examplify how E-M expectation becomes more powerful with describing details of an image with higher number of clusters.

| Original | `<K = 2>` | `<K = 4>` | `<K = 8>` |
|--------------|----------------|-----------------|-----------------|
| ![Original](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/d3846632-aa29-4bca-a47c-f0afb42f896b) |![image](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/4e00421b-b1d9-4c08-9470-d32c37d3bf4e) | ![image](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/74106d98-c3dd-49ab-98f9-66760df74d3e)| ![image](https://github.com/kimhyeonejun/K-means-clustering-and-EM-expectation/assets/103301952/475e5f6a-0de4-4a3d-898a-29124dc862eb)|
