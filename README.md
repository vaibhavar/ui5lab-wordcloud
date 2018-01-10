## ui5lab-wordcloud
"ui5lab.wordcloud" library contains a control "WordCloud" to render tag clouds in UI5.

## Preview
![image](https://user-images.githubusercontent.com/7377491/34742350-dcb2e33e-f5ab-11e7-8083-f37d9eafebf6.png)

## Preview with Icons only
![image](https://user-images.githubusercontent.com/7377491/34742364-f2f8e800-f5ab-11e7-85a6-a9d3c3ec4b0a.png)


Word clouds are customizable with the following options -
- **words** : An aggregation of Word; each word can have different weight. The control will render font-size with respect to the weight of each word. Words may also contain "icons".

- **rotate** : Word clouds look more fun when words are rotated randomly.

- **randomOrder** : The control can render words in random order if set to true..

- **colors** : A color palette can be defined.

- **fontSizes**: A list of font sizes to display words as per their "weight".



# Running the samples

Install all the resources
~~~~
 npm install
~~~~

Start grunt build
~~~~
 npm start
~~~~

Once the built has completed, open up the UI5Lab browser sample ([link](http://localhost:8083/test-resources/ui5lab/browser/index.html "UI5Lab browser sample")) in your browser and you should see ui5lab.wordcloud library added in the list.
