# Audio-to-video-transtlator

Sign language serves as a vital communication medium for the hearing-impaired community, yet a significant communication gap persists between them and non-sign language users. This project aims to bridge this gap by
developing an Audio to video sign language translator using RNN , Natural Language Processing (NLP) and Deep learning. The system captures spoken audio, processes it using speech-to-text models, and converts the
resulting text into corresponding sign language gestures. These gestures are visualized through an animated avatar that displays the signs in a video format. The use of an avatar ensures a dynamic and realistic representation of sign language, making it intuitive for the end-user.

The process follows these steps
•	Text Processing & Conversion
•	Input English text is analyzed using NLP techniques and restructured into sign language grammar.
•	The system matches each word with its corresponding sigML files using RNN. As RNN is used for sequential data processing.
•	SiGML Generation
•	The HamNoSys notation is converted into SiGML code, which provides detailed movement descriptions for a virtual avatar.
•	SiGML defines the timing, transitions, and gestures required to animate sign language properly.
•	3D Animation Rendering
•	The SiGML file is fed into a sign language avatar system (such as JASigning, an open-source SiGML-based avatar).
•	The avatar interprets the SiGML data and produces real-time signing animations that visually represent the translated text.
