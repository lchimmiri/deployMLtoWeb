# Deploy TF Models to the Web
<pre>
1. Create a TF model and save it as a HDF5 file which will be translated into the TensorFlow.js web format.
2. To convert the model, we first need to <b>pip install tensorflowjs</b>. Once installed, we run the tensorflowjs_converter from the command line <b>tensorflowjs_converter --input_format=keras model.h5 model_js</b>
3. Here, we are telling tensorflowjs_converter to expect the keras model format. That .json file is our web-enabled model, ready for use in JavaScript.
4. Embed the model json in html and execute it.
</pre>
