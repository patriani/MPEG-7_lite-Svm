# MPEG-7_lite/Svm
O projeto em questão se trata de uma discussão e exercício do método Support Vector Machine sobre 720 imagens do conjunto de dados MPEG-7. Foram utilizados diferentes kernels do SVM e a versão Lite do conjunto de dados está disponibilizada em: *\Train* e *\Test*.

Ao final do estudo conclui-se que o melhor modelo para este dataset foi o Gaussiano ({'C': 10, 'gamma': 1, 'kernel': 'rbf'}). O conjunto utilizado se apresentou em versão lite devido o estudo ter sido um projeto de disciplina. Porém, recomenda-se a reprodução da metodologia para o conjunto íntegro, uma vez que o método Support Vector Machine não lida tão bem com amostras pequenas.

Abaixo pode-se verificar a matriz de confusão do conjunto de teste e suas métricas, em que os rótulos de 0 a 3 representam respectivamente as classes de figura: maçã, morcego, besouro e osso.

<p align="center">
  <img src="https://user-images.githubusercontent.com/43487367/218860652-a2ec665a-c40f-4f36-a110-9133cb6e15c2.PNG" /> 
</p>

<br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/43487367/218860774-cb15f9e4-4e28-48cc-8c54-8e3307256fca.PNG" /> 
</p>
