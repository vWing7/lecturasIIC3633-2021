# Crítica: Collaborative Filtering Recommender Systems

Este paper presenta una visión general de "Collaborative Filtering" (CF), se exponen diversos aspectos relacionados a CF, principalmente la historia, usos, algoritmos específicos y desafíos en el diseño e implementación de esta tecnología. Adicionalmente se plantea una nueva forma de clasificar algoritmos de CF que los separa en probabilísticos y no probabilísticos.

Es importante notar que en el paper, la mayoría de las cosas se exponen de forma general, por lo cual puede servir como buen texto introductorio al área de CF, pero para profundizar se necesita leer otros textos más especializados, pudiendo ser un buen inicio usar los textos referenciados en este paper.

En general los algoritmos mostrados se entienden bien, pero en los desafios prácticos de Association Rule Mining, no entiendo bien por qué perder la relación numérica entre los ratings es algo negativo, considerando que esto podría llegar a ser útil si no necesariamente se quiere recomendar algo con un rating alto, por ejemplo, se puede querer buscar elementos con bajo rating no para disfrutarlos, sino para estudiarlos, o hacer reviews de estos.

Otro aspecto que me pareció relevante es el uso de tags para recomendar en conjunto con CF, ya que en mi experiencia personal, los tags son muchas veces más importantes que el rating de un producto, por ejemplo los géneros en los que cae una película o videojuego, si coinciden con mis gustos, pueden hacer que quiera ver una pelicula a la que según una predicción independiente le daría bajo rating.

Finalmente, cabe mencionar que el paper fue publicado en el año 2007, por lo que es posible que aspectos que se dejan abiertos a discusión futura, como el mismo uso de tagging mencionado anteriormente ya estén implementados de mejor forma, y que CF se haya propagado más que solo a grandes empresas o centros de investigación como el paper dice que era cuando se publicó.