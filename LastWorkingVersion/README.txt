Files:
motor-imagery-bci-1-acquisition_New --> Scenario used to record 3 features using motor imagery paradigm
motor-imagery-bci-graz-stimulator --> LUA script that goes with the motor imagery acquisition. It is different from the original provided by tutorials as this recognizes and labels a third class
motor-imagery-1-[2022.07.24-15.09.36] --> Recording 3 artifacts with motor imagery paradigm
Trainer_old --> File to train LDA classifier using a recording file. Overall accuracy around 95%
classifier6 --> Output from the trainer_old file. This is the configuration for the trained classifier
Classifier2_old --> Scenario for test (with reader file, with accuracy around 90%) or online test (with acquisition client)

Labels:
OVTK_GDF_Left (eye blink)
OVTK_GDF_Right (chew)
OVTK_GDF_Up (sexy move)

Common errors:
Wrong file directories were required files are (manually select the correct ones if necessary)
Trying to edit CSV files while having them open (disable CSV writer boxes if you wont need the files)
