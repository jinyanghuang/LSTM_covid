# LSTM_covid
<h1>Data set</h1>
<p>data sets are download from (https://github.com/CSSEGISandData/COVID-19) Data Repository by Johns Hopkins CSSE</p>
<h1>Idea</h1>
<p>Use LSTM model to predict new confirmed cases. Create a model for all country instead one for each.</p>
<h2>data prepossessing</h2>
<p>normalize data by dividing population density. </p>
<h2>model</h2>
<p>library: keras with tensorflow 1.15 </p>
<p>loss function: mean square error </p>
<p>optimizer: admm </p>
<P>create 2 model. First one is train on individual country and second one is train on all countries. <P>
