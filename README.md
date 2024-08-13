# Computer Vision: Counting Cars in Video
## Computer vs human eyes


Hello Internet!

Even non living things have vision! well... not really 🙂‍↔️🙃

This Jupyter notebook provides a step-by-step guide on how to use an open-source Object Detection (OD) model from Hugging Face to count cars in a video. The notebook leverages the `transformers` and `opencv-python` libraries to handle the tasks of processing video input and producing a labeled output video with a real-time counter. Additionally, `matplotlib` is used to display images for visualization purposes.

This script is inspired by various computer vision tutorials and adapted to demonstrate practical applications of machine learning in video analysis.

Recommendations:
* `transformers` (Library for state-of-the-art machine learning models)
* `opencv-python` (Library for computer vision tasks)
* `Python 3.10` (click on top right corner to change version)
* `matplotlib 3.4.3` (Library for plotting graphs, but in this case it is used to display images)
* `torch` (Deep learning library, required for running the Hugging Face models)

## Video Sources

For this tutorial, we'll be using free stock videos from Pexels. You can use your own videos or download these examples:

- People_walking: https://www.pexels.com/video/black-and-white-video-of-people-853889/ (works ok)
- Dogs in snow: https://www.pexels.com/video/dogs-enjoying-the-snow-4157418/ (works meh/bad)
- Dogs playing: https://www.pexels.com/video/dogs-playing-854179/ (works well!)
- Cars: https://www.pexels.com/video/cars-on-highway-854671/ (works well!)
