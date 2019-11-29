<style>
.btn {
  float: left;
  background-color: transparent;
  border: none;
}
  img {
  display: inline-block;
  margin-right: 10px;
  vertical-align: middle;
}

.content-holder {
  display: inline-block;
  vertical-align: middle;
}
</style>

<h2>Abstract</h2>
<p style="text-align: justify;">Word Sense Disambiguation (WSD) is the task of associating a word in context with one of its meanings. While many works in the past have focused on raising the state of the art, none has even come close to achieving an F-score in the 80% ballpark when using WordNet as its sense inventory. We contend that one of the main reasons for this failure is the excessively fine granularity of this inventory, resulting in senses that are hard to differentiate between, even for an experienced human annotator. In this paper we cope with this long-standing problem by introducing Coarse Sense Inventory (CSI), obtained by linking WordNet concepts to a new set of 45 labels. The results show that the coarse granularity of CSI leads a WSD model to achieve 85.9% F1, while maintaining a high expressive power. Our set of labels also exhibits ease of use in tagging and a descriptiveness that other coarse inventories lack, as demonstrated in two annotation tasks which we performed. Moreover, a few-shot evaluation proves that the class-based nature of CSI allows the model to generalise over unseen or under-represented words.</p>
  
<h3 style="vertical-align:middle;"> Reference </h3>
  
  <a href="https://pasinit.github.io/papers/lacerra_etal_aaai2020.pdf" download target='_blank'>CSI: A Coarse Sense Inventory for 85% Word Sense Disambiguation</a>
  ```
    @inproceedings{lacerraetal:2020
    title={CSI: A Coarse Sense Inventory for 85% Word Sense Disambiguation},
    author={Lacerra, Caterina and Bevilacqua, Michele and Pasini, Tommaso and Navigli, Roberto},
    booktitle={Proceedings of the 34th Conference on Artificial Intelligence},
    publisher={Association for the Advancement of Artificial Intelligence}
    year={2020}
    }
  ```

<h3>Authors</h3>

<div>
<img class="img" src="https://raw.githubusercontent.com/caterinaLacerra/CSI/master/_images/dino4.jpg" width="60px" >
<p class="content-holder">Caterina Lacerra<br/>PhD student @ Sapienza<br/>
lacerra [at] di.uniroma1.it</p>
</div>

<div>
<img class="img" src="https://raw.githubusercontent.com/caterinaLacerra/CSI/master/_images/dino2.jpg" width="60px">
<p class="content-holder">
  <a href="https://mbevila.github.io/">Michele Bevilacqua</a><br/>
  PhD student @ Sapienza<br/>
  bevilacqua [at] di.uniroma1.it
</p>
</div>

<div>
<img class="img" src="https://raw.githubusercontent.com/caterinaLacerra/CSI/master/_images/dino3.jpg" width="60px">
<p class="content-holder">
  <a href="https://pasinit.github.io/">Tommaso Pasini</a><br/>
  Post-Doc @ Sapienza<br/>
  pasini [at] di.uniroma1.it
</p>
</div>

<div>
<img class="img" src="https://raw.githubusercontent.com/caterinaLacerra/CSI/master/_images/dino1.jpg" width="60px">
<p class="content-holder">
  <a href="http://wwwusers.di.uniroma1.it/~navigli/">Roberto Navigli</a><br/>
  Full Professor @ Sapienza<br/>
  navigli [at] di.uniroma1.it
</p>
</div>
