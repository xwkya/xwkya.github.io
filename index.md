---
layout: default
---

# Kya's Profile
## About me
* Paul
* 21 Earth laps around the sun
* Machine Learning Engineer and Mathematician


I'm currently in a double diploma Msc by research at the **National University of Singapore**. I have studied in French top Engineering School **Centrale Supélec** for my Masters degree, focusing on fundamental Mathematics and Engineering. I hold a Bachelor's degree in mathematics from the [#1 school in mathematics in the world ](https://www.shanghairanking.com/rankings/gras/2021/RS0101), **Université Paris-Saclay**. I have studied in the intense _Classe Préparatoire aux Grandes Ecoles (CPGE)_ **Lycée Thiers** for 2 years to prepare for the entrance examination for Engineering School.

> My main motivation is to make models that will one day impress the world



## Mathematics projects

Here is a small sample of the projects related to mathematics that I have worked on.

### Onera Liner Optimisation

Optimizing the accoustic liner repartition in a plane engine to minimize the noise percieved in cities by planes. Given a budget equal to a fraction of the available area, develop analytical and numerical tools to find the best repartition of the liner over the propulser's contour.

> The optimized liner repartition using genetic algorithm.
![Optimized Liner](liner_optimized_beta0.4.png)

<br/>

> The Form derivation obtained on Helmoltz Equation for the first time in our paper.
![Equation](equations8.JPG)


[Link to the LateX report](https://xwkya.github.io/rapport_projet_S8(2).pdf)

### JetX - Gambling website statistics

Scraping and analysis of thousands of data about a specific online casino game. Attempt to predict the data with a RNN depending on the total amount at stake and the number of players. No correlation found.

> Sample of analysis made
> 
> ![Probability of winning](prob_winning_100_compare.png)


[Link to the LateX report](https://xwkya.github.io/JetX(4).pdf)


### Record Theory \[French report\]

Development of a statistical test on data distribution based on number of records. Analysis of best permutation sample to augment the data.

>Statistical test formula based on the number of records
![Equation Records](equation_records.JPG)

[Link to the LateX report (In french)](https://xwkya.github.io/Stats_des_records.pdf)

## Machine Learning Projects

### Amazon comments sentiment analysis

Notebook to learn how to process sentences using lemmatization, embedding, SBERT preprocessing and LSTM cells. One of the other aspect is cleaning and working with huge amount of data. The final product is fun to play with and the high-low accuracy (binary classification >=4 stars or <=3 stars) is 90%.

> The user can input his own comment and the model will predict how many stars the user would have assigned based on the comment.

```python
sentence_pred_batch("Although I thought it would be funny, I was a bit\
      disappointed by the poor performance of the actors and the gross jokes.")
 >>> 2.52000
 
high_low_accuracy=(np.sum(confusion_matrix[:3,:3])+np.sum(confusion_matrix[3:,3:]))/np.sum(confusion_matrix)
print("high/low accuracy: ", high_low_accuracy)
 >>> high/low accuracy:  0.89588
```

### Explanations
```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
