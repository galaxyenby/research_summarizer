# summarize_app
A potential website-app to summarize research papers and present important keywords.

This app's front-end uses Flask to coneect user input (which would be a HTML file of the research paper) and
outputs a summary of the paper using the natural-language-processing (NLP) tool "Gensim" to
provide a summary of the paper, along with keywords. Gensim's summarizer is an "extractive" summarize
which means it finds the most important sentences in the text, along with subject-specific keywords,
and presents it back to the user.

I'm hoping this tool would be useful for marginalized students in STEM related fields, so if they don't have the
time to read through academic papers, they can use this summarization app to get the gist of the research
article (that they might need for their class, or to talk to professors/TAs/postdocs for potential undergraduate research).
