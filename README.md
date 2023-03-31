# test_case_cv
REST-service for checking if two frames come from the same video
Using mobilenet for checking if two embedding are similar (cosine distance)
Using flask for http serving. 
Using onnxruntime for portability (lightweight, no dependencies like torch or TF)

## Build docker and run it

`docker build -t test_case .`

`docker run -it test_case:latest`

## Run client for tests:

`python client.py`
