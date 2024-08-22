# Gesture-Genie

### What it does: 
Gesture Genie is a web application that bridges the gap between the deaf and hearing communities by translating spoken language into American Sign Language (ASL) using real-time video and tone detection. Additionally, the application offers sign-to-speech functionality, translating ASL gestures into spoken language using computer vision techniques.

### Inspiration: 
Just in the United States, 11 million people are deaf, of which half a million use ASL natively. For people who are deaf to communicate with those who are hearing, and therefore most likely not fluent in sign language, they’re constricted to slower methods of communication, such as writing. Similarly, for people who don’t know sign language to immediately be able to communicate comfortably with someone who is deaf, the only options are writing or lip-reading, which has been proven to only be 30-40% effective. By creating Gesture Genie, we aim to make the day to day lives of both the deaf and hearing communities significantly more tension-free.

### How we built it:

1) Sign Gestures to Text (https://youtu.be/3gNQDp1nM_w)

- We used OpenCV to to capture video from the user which we processed into
- We used Google MediaPipe API to detect all 21 joints in the user's hands
- Trained neural networks to detect and classify ASL gestures

2) Voice to Sign Language Gestures (https://youtu.be/mBUhU8b3gK0?si=eIEOiOFE0mahXCWI)

- Web scraping online dictionaries to show videos for ASL gestures or fingerspelling
- Merging videos of individual sign language words/gestures

### Next Steps:

We are most proud of being able to recognize action-based sign language words rather than simply relying on fingerspelling to understand the sign language that we input. Next, we hope to be able to incorporate more phrases/action based gestures, scaling our product to be able to work seamlessly in the day-to-day lives of those who are hard of hearing. We also aim to use more LLMs to better translate the text, recognizing voice and facial emotions as well.
