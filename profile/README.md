# Welcome to Team.Fairy🧚

we hope to provide comfort and make a world where everyone can coexist.<br>
Fairy-eye project is a “Walking assistance application” which can help individuals such as visually impaired.

## Application - Fairy Eye

https://github.com/Project-Fairy/fairy-eye

## Problems which visually impaired struggles

1. White cane troubles to detect obstacles floating in the air, and guide dogs can be disturbed by various factors such as odors.
2. Auditory signal system informs the signal has been changed only once, does not provide information about how much green signal remained.
3. users are required to report the breakdown in spite of malfunctions are frequent.

## How can we solve these problems

Fairy-eye detects the conditions around users by camera and guides them. Also, warns unexpedted situations such as motorcycles.

### Mediapipe

We used 'MediaPipe' for identifying object.<br>
MediaPipe is composed of Python and TensorFlow, and we implemented it using Colab.<br>
MediaPipe provides light model and easy to use in low-spec environments.<br>
It supports various platforms such as Android, iOS, Desktop, and Web.<br>
Also had the advantages of providing pre-optimized code, ready to use without complicated configuration processes, and free open source for cost-free use.

#### mediapipe-modal-custom
https://github.com/Project-Fairy/mediapipe-modal-custom

### Android

For more easier useage of trained model, an Android phone with a high penetration rate was used.<br>
The Android application was developed using Kotlin.<br>

### AI Studio

To connect with Gemini, we experimented with using AI Studio which allowed for direct invocation on Android devices.
