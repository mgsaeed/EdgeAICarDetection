# Integrate the Inference Engine in An Edge App

1. Convert a bounding box model to an IR with the Model Optimizer.
2. Pre-process the model as necessary.
3. Use an async request to perform inference on each video frame.
4. Extract the results from the inference request.
5. Add code to make the requests and feed back the results within the application.
6. Perform any necessary post-processing steps to get the bounding boxes.
7. Add a command line argument to allow for different confidence thresholds for the model.
8. Add a command line argument to allow for different bounding box colors for the output.


```bash
python app.py -m {your-model-path.xml}
```
