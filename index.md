<style>
.btn{
  border: none;
  background-color: transparent;
}
.btn:hover {
  background-color: RoyalBlue;
}
</style>

<h2>Abstract</h2>
<p style="text-align: justify;">Word Sense Disambiguation (WSD) is the task of associating a word in context with one of its meanings. While many works in the past have focused on raising the state of the art, none has even come close to achieving an F-score in the 80% ballpark when using WordNet as its sense inventory. We contend that one of the main reasons for this failure is the excessively fine granularity of this inventory, resulting in senses that are hard to differentiate between, even for an experienced human annotator. In this paper we cope with this long-standing problem by introducing Coarse Sense Inventory (CSI), obtained by linking WordNet concepts to a new set of 45 labels. The results show that the coarse granular-ity of CSI leads a WSD model to achieve 85.9% F1, while maintaining a high expressive power. Our set of labels also exhibits ease of use in tagging and a descriptiveness that other coarse inventories lack, as demonstrated in two annotation tasks which we performed. Moreover, a few-shot evaluation proves that the class-based nature of CSI allows the model to generalise over unseen or under-represented words.</p>

### Reference <button class="btn"><i class="far fa-bookmark"></i></button>
<a href="https://pasinit.github.io/papers/lacerra_etal_aaai2020.pdf" download target='_blank'>CSI: A Coarse Sense Inventory for 85% Word Sense Disambiguation</a>
### Authors
Caterina Lacerra, PhD student @ Sapienza<br/>
lacerra [at] di.uniroma1.it


[Michele Bevilacqua](https://mbevila.github.io/), PhD student @ Sapienza<br/>
bevilacqua [at] di.uniroma1.it


[Tommaso Pasini](https://pasinit.github.io/), Post-Doc @ Sapienza<br/>
pasini [at] di.uniroma1.it


[Roberto Navigli](http://wwwusers.di.uniroma1.it/~navigli/), Full Professor @ Sapienza<br/>
navigli [at] di.uniroma1.it


