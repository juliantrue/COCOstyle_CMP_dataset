# COCOstyle CMP Facades Dataset
This repo provides the [CMP dataset](http://cmp.felk.cvut.cz/~tylecr1/facade/) in format convenient for training Deep Neural Networks. Without a standard dataset format, it can be quite tedious writing new parsers for each new dataset. [The COCO dataset](http://cocodataset.org/#home) provides a reusable approach to dataset formatting and hence, I have converted the popular facade database to this format to save time. This dataset contains both the CMP facade base dataset as well as the CMP facade extended dataset. 

# Usage
- Clone this repository into a folder named "facades".
- Download and install the [cocoapi](https://github.com/cocodataset/cocoapi).
- Use according to cocoapi's documentation

# Citations
`@INPROCEEDINGS{Tylecek13,
  author = {Radim Tyle{\v c}ek and Radim {\v S}{\' a}ra},
  title = {Spatial Pattern Templates for Recognition of Objects with Regular Structure},
  booktitle = {Proc. GCPR},
  year = {2013},
  address = {Saarbrucken, Germany},
}<Paste>`

