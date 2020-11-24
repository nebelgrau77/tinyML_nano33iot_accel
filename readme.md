### Smart dumbbell with Arduino Nano 33 IoT and EdgeImpulse

1. Data acquisition with a smartphone (how to connect a smartphone to EdgeImpulse?)
   1. Collect training data
   2. Collect test data
   3. Check sensor orientation
2. Model building
   1. include anomaly detection
   2. Go to Keras Expert mode
   3. Download iPython notebook
3. Model training
   1. test accuracy
   2. experiment with settings
4. Testing
5. Live classification
   1. set up the board code in PlatformIO (or plain Arduino IDE)
   2. make sure frequency is correct
6. Deployment
   1. Build Arduino library
   2. Replace sensor library
   3. Add fixes for float vs integer printing
   4. Add fixes for faster DSP processing
   5. Flash the board