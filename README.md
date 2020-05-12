# Android Application to Classify Dog Breeds

## 1. Train the TensorFlow Lite mode
The model was trained on [Stanford Dogs dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) which was trained on 20,580 images of 120 dog breeds.

Download the trained model and labels and store it in the assets folder.
```bash
#Path to assets directory

/lite/examples/image_classification/android/app/src/main/assets/
```

## 2. Clone the repository
Clone the [TensorFlow Lite examples](https://github.com/tensorflow/examples.git) repository on your local machine.

```bash
git clone https://github.com/tensorflow/examples.git
```

## 3. Enable developer options and USB debugging on your Android device
. Android 9 (API level 28) and higher: Settings > System > Advanced > Developer Options > USB debugging
. Android 8.0.0 (API level 26) and Android 8.1.0 (API level 26): Settings > System > Developer Options > USB debugging


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
