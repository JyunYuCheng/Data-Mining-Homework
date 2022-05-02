# Question 1 : Clustering and PCA

## Run the PCA and Clustering

### Clustering part

### Assess : Clustering

#### Color

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-6-1.png)
According to this figure, we can see that we may distinguish wines by
fixed.acidity and volatile.acidity

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-7-1.png)
By clustering, We can see that one group is on the left, and the other
group is on the right.

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-8-1.png)

This is the true color group of wines, compare to the above
figure(clustering), we can see that clustering can help us distinguish
the color of wine.

#### Quality

Now we are going to see that whether clustering works for quality Now we
see the true quality figure
![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-9-1.png)
We can see that these figures are very disordered, so we can’t use it to
determine Because it is difficult to see which one can help us to
distinguish, so we decide to use mean value of them to see which may
work.
![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-10-1.png)
We can see that there are 4 properties(alcohol,density,citric.acid and
Free.sulfur.dioxide) may be used to distinguish the quality because they
looks like they have some trends.

##### clustering labels

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-11-1.png)
We can see that we still can’t catch the difference among wines
accurately,

##### Orginal label

Now we see the true quality of wines
![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-12-1.png)
Compare the above 2 figures, we can know that it’s very difficult to
distinguish the quality of wines by use clustering.

### PCA part

#### colors

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-15-1.png)
From this figure, we can see that PC1 and PC2 may have some trends, so
we may use it to distinguish color of wines

Then we plot it into one figure to see their abilities of distinguish

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-16-1.png)
We can see that the points in the left are usually red wines, in the
right are usually white wines. So PCA can distinguish the color of wines
successfully.

#### quality

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-17-1.png)

From this figure, we can see that it’s difficult to distinguish the
qualities by PCA

In order to assure this statement, we decide to use the median values to
find which PC have ability to distinguish the qualities

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-18-1.png)
From this figure, we can see that PC2 and PC3 may help us to distinguish
the qualities

![](Exercise4-1-Jonathan-_files/figure-markdown_strict/unnamed-chunk-19-1.png)
However, according to this figure, we still can’t use PCA to distinguish
the quality successfully.

## Conclusion

Whether PCA or Clustering, they can distinguish the colors of wines
successfully, but both of them can’t distinguish the qualities of wines
Although PCA is better than Clustering, but it still doesn’t have good
ability to distinguish the qualities of wines
