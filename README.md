
# FaceSearch
       █▀▀ █▀▀█ █▀▀ █▀▀   █▀▀ █▀▀ █▀▀█ █▀▀█ █▀▀ █  █       
       █▀▀ █▄▄█ █   █▀▀   ▀▀█ █▀▀ █▄▄█ █▄▄▀ █   █▀▀█       
       ▀   ▀  ▀ ▀▀▀ ▀▀▀   ▀▀▀ ▀▀▀ ▀  ▀ ▀ ▀▀ ▀▀▀ ▀  ▀       

FaceSearch: Searches for faces in a given image using the Google Reverse Image Search engine.

## Installation


First clone this repo. Now, to install the dependencies and create the alias for FaceSearch, run the `install.sh`.
  ``` bash
  bash install.sh
  ```

## Usage
Once it finishes, you can now use the following command on the terminal to detect and search for the faces in any image.
``` bash
facesearch path/to/Image
```
**Also**, note that the `path/to/Image` can be an internet URL as well! (prefixed with http: or https:)
So, you can just drag an image off the internet over the terminal to get its URL pasted over there and search for faces in it using FaceSearch. Really convenient.

## Examples
Test image:

![alt text](./test_img/test.jpg "Test image")

On command line:
```
abhar-pc:~/FaceSearch$ facesearch test_img/test.jpg
[ INFO:0] Initialize OpenCL runtime...
Uploading image..

```
Output Window:

![alt text](./test_img/test_img1.png "The output window")


Image Source: [Pinterest](https://images.app.goo.gl/JsAJL46xi9PrhW7j8)
