# Gesture-Genie

Inspiration
Just in the United States, 11 million people are deaf, of which half a million use ASL natively. For people who are deaf to communicate with those who are hearing, and therefore most likely not fluent in sign language, they’re constricted to slower methods of communication, such as writing. Similarly, for people who don’t know sign language to immediately be able to communicate comfortably with someone who is deaf, the only options are writing or lip-reading, which has been proven to only be 30-40% effective. By creating Gesture Genie, we aim to make the day to day lives of both the deaf and hearing communities significantly more tension-free.

What it does
Two Way Sign Language Translator that can translate voice into visual sign language and can translate visual sign language into speech. We use computer vision algorithms to recognize the sign language gestures and translate into text.

How we built it
Sign Gestures to Text

We used OpenCV to to capture video from the user which we processed into
We used Google MediaPipe API to detect all 21 joints in the user's hands
Trained neural networks to detect and classify ASL gestures
https://youtu.be/3gNQDp1nM_w

Voice to Sign Language Gestures

Voice to text translation
Text to words/fingerspelling
By web scraping online ASL dictionaries we can show videos for all ASL through gestures or fingerspelling
Merging videos of individual sign language words/gestures
https://youtu.be/mBUhU8b3gK0?si=eIEOiOFE0mahXCWI

Challenges we ran into
The biggest challenge that we faced was incorporating the backend into the React/node.js frontend. We use OpenCV for the backend, and we needed to ensure that the camera's output is shown on the front end. We were able to solve this problem by using iFrames in order to integrate the local backend into our combined webpage.

Accomplishments that we're proud of
We are most proud of being able to recognize action-based sign language words rather than simply relying on fingerspelling to understand the sign language that we input. Additionally, we were able to integrate these videos from our backend into the front end seamlessly using Flask APIs and iFrames.

What we learned
What's next for Gesture Genie
Next, we hope to be able to incorporate more phrases/action based gestures, scaling our product to be able to work seamlessly in the day-to-day lives of those who are hard of hearing. We also aim to use more LLMs to better translate the text, recognizing voice and facial emotions as well.
