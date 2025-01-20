Problem Statement :-
In the current hiring landscape, recruiters face the challenge of efficiently screening and shortlisting large volumes of resumes to identify the most suitable candidates for job openings. 
The traditional manual review process is time-consuming, resource-intensive, and often inconsistent due to subjective decision-making. 
As the volume of job applications grows, particularly for popular positions, it becomes increasingly difficult to identify qualified candidates in a timely manner.
To address this issue, there is a need for an AI-based resume ranking system that can automatically evaluate and rank resumes based on their relevance to specific job descriptions. 
This system should leverage Natural Language Processing (NLP) and Machine Learning (ML) techniques to analyze and score resumes according to key criteria, such as skills, experience, and qualifications, providing recruiters with a prioritized list of top candidates. 
Such a system will improve recruitment efficiency, reduce hiring times, and assist organizations in selecting the best talent in a consistent and objective manner.

NLP Techniques and Models Used in the Project
a) Text Extraction: It explains how text is extracted from unstructured resume files (PDFs or DOCX), preparing it for analysis.

b) 	Named Entity Recognition (NER): Describing NER as a technique that identifies specific entities in text, such as names, email addresses, locations, and dates. In our project, we have used spaCy’s NER to recognize candidate names, email-id’s and contact details which are essential for the ranking output.

c) 	Tokenization and Text Cleaning: Briefly describing tokenization, where text is broken down into individual words or phrases, which helps to create structured data for analysis.

d) Text Vectorization Using BERT: BERT (Bidirectional Encoder Representations from Transformers) is a state-of-the-art transformer model developed by Google, known for capturing deep contextual relationships between words. Unlike traditional vectorization techniques like TF-IDF, which are based on word frequency, BERT understands the context in which words appear, allowing for a more accurate representation of complex language structures in resumes and job descriptions.

