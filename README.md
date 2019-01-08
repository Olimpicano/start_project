# Стартовый проект с gulp  ![Test Status](https://travis-ci.org/nicothin/NTH-start-project.svg?branch=master) [![devDependencies Status](https://david-dm.org/nicothin/NTH-start-project/dev-status.svg)](https://david-dm.org/nicothin/NTH-start-project?type=dev) [![dependencies Status](https://david-dm.org/nicothin/NTH-start-project/status.svg)](https://david-dm.org/nicothin/NTH-start-project)

За основу взят [ссылка](https://github.com/nicothin/NTH-start-project)

#модификации

*помимо создания блока createBlock имеется:
  1. createSec создает стандартную разметку для блока с *container* и *row*, прописывает в scss миксины к ним
  2. createDouble помимо стандартной разметки создает две *колоны* и прописывает миксин с col = 6

*убрал все линшие блоки 
*блоку *btn* убрал всю стилизацию, работает только миксин пага
*установил зависимость bootstrap, основная типографика, кнопки, цвета берутся от него, подлкючаем или отключаем его модули в файле bootstrap.scss
*установлен [bootstrap.native](https://github.com/thednp/bootstrap.native)
*установлен bable
*на проект подтягивается *jquery* но по умолчанию его нет в projectConfig