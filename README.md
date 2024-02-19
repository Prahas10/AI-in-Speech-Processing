# AI-in-Speech-Processing

## Course Learnings

## Lab 1 - Librosa

Librosa is a powerful Python library for working with audio data. Throughout the course, we covered various aspects of Librosa, including:

- **Usage of audio files and loading audio recordings:**
- **Visualization of audio signals:**
- **Feature Extraction:**
- **Effects Creation - noise removal, Segmentation, etc.:**
- **Sampling:**

## Lab 2 - First Derivative, Zero Crossings

- **First Derivative Calculation using Finite Difference Method**<br>
  Computing the first derivative of a signal is essential for understanding its rate of change over time. The finite difference method provides a straightforward approach to estimate the derivative at discrete points by computing the difference between neighboring samples. This method is widely used in signal processing due to its simplicity and efficiency.

- **Detecting Zero Crossings in a Signal**<br>
  Zero crossings in a signal occur when the signal changes polarity, i.e., when it transitions from positive to negative or vice versa. Detecting these zero crossings is valuable for identifying significant points in the signal where transitions occur. This information is often used for event detection, feature extraction, and boundary detection in various signal processing applications.

- **Analyzing Zero Crossings in the First Derivative Signal**<br>
  Analyzing the zero crossings in the first derivative signal provides insights into the local variations and trends of the original signal. By examining the locations and frequencies of these zero crossings, patterns and anomalies in the original signal can be identified. This analysis is particularly useful in applications such as motion detection, audio processing, and biomedical signal analysis, where understanding the dynamics of the signal is crucial.

## Lab 3 - librosa.trim(), librosa.split()

- **Trim Silence from Speech Signal (librosa.effects.trim())**<br>

The `librosa.effects.trim()` function is utilized to remove silence segments from the beginning and end of a recorded speech signal. By setting an appropriate threshold, this function automatically detects and trims silence portions, thereby focusing on the active speech segments. This process enhances the clarity and intelligibility of the speech signal, making it more suitable for analysis or playback.

- **Split Speech Signal with Detected Silences (librosa.effects.split())**<br>

The `librosa.effects.split()` function allows for the segmentation of a recorded speech signal based on detected silences. By adjusting the `top_db` parameter, users can control the sensitivity of silence detection, influencing the quality and granularity of the resulting split segments. This capability enables the isolation of distinct speech segments, facilitating further analysis or processing of individual segments.
