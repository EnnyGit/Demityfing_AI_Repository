# A deep dive into AI and ChatGPT

# Introduction
This comprehensive report delves into the realm of Artificial Intelligence (AI), using ChatGPT as a case study to illustrate AI's capabilities and applications. AI is framed as a computational entity that, while not capable of human thought, can learn, reason, self-correct, solve problems, and interact in ways that emulate human behavior, leveraging algorithms and data.

In the ever-evolving world of technology, Artificial Intelligence (AI) represents a paradigm shift, especially in the realm of programming where I have devoted my professional life. To me, AI signifies a leap towards a more automated future, where the mundane aspects of coding become streamlined, allowing creativity and efficiency to flourish. I still remember my first encounter with ChatGPT; it was nothing short of transformative, reshaping the landscape of development work as I knew it. The adoption of this tool by my peers was swift, a testament to its profound impact on our collective workflow.

The utility of ChatGPT extends beyond mere code generation; it serves as a digital muse for brainstorming sessions and a knowledgeable companion when delving into new domains of expertise. My appreciation for AI may stem from a programmer’s perspective, a blend of fascination and a hint of understanding of its underlying mechanics. There's a sense of wonder that accompanies my curiosity about how AI will further integrate into the tapestry of our daily lives.

Despite its regular use, ChatGPT remains somewhat of a mystery—a 'black box'. While I grasp the basics of AI operations, the intricate details of its internal processes elude me. It's a delightful tool to wield, yet the opacity of its inner workings and the implications for aspects such as privacy linger in my mind as areas of concern.

Throughout the development of this paper, AI, specifically ChatGPT, has been an instrumental asset. It has rephrased and refined my initial drafts, drawing from various sources, including websites and PDFs. In striving for a balanced perspective, I tasked ChatGPT with presenting both positive and negative viewpoints on topics, from which I then crafted my nuanced narrative. The introduction you’re reading now is also born from this digital forge. While I lean on AI for its insights, I diligently corroborate its knowledge with factual data from established online resources.

This paper is as much a product of AI as it is of my own thought process, embodying a collaborative synergy between human intent and machine intelligence. As we advance into the future, I look forward to witnessing—and shaping—the role of AI in our professional and personal lives.


# Part I: Problem Selection, Definition & Motivation + Human in the Loop
## 1.1 Artificial Intelligence definition
Artificial intelligence is the field of study and application that involves crafting smart machines and software that can solve problems and make decisions in a way that, at times, resembles human cognition but can also go beyond human capabilities or methods. (What is artificial intelligence (AI) ? | IBM, z.d.)
## 1.2 Characteristics of AI
Artificial intelligence harnesses machine learning and deep learning to excel in problem-solving and predictive analysis. It learns from vast datasets through sophisticated algorithms, a process integral to its ability to self-correct and improve over time. This learning is complemented by AI's reasoning capabilities, which mimic human thought to make decisions and solve complex problems, evident in technologies that require interaction, such as chatbots and virtual assistants. (What is artificial intelligence (AI) ? | IBM, z.d.)

Reasoning in AI spans from logical deduction to the adaptability required to handle new information, reflecting the use of both monotonic and non-monotonic reasoning. These methods illustrate AI's multifaceted approach to tackling challenges and making informed decisions, highlighting its cognitive process that parallels human reasoning and judgment. (Reasoning in Artificial Intelligence - JavatPoint, z.d.)

## 1.3 Info-graphic
![AI Info-graphic](/assets/info-graphic-ai.png)
This infographic provides a snapshot of the various artificial intelligence (AI) technologies segmented into three categories: Language Models, AI Tools (ChatGPT), and Computer Vision. On the language models front, it highlights GPT-4, BERT, and T5, which are renowned for their natural language processing capabilities, ranging from text generation to sentiment analysis and translation. At the core of the AI tools section is ChatGPT, which acts as an intermediary, leveraging the power of language models and computer vision to understand and generate human-like text and images. Lastly, the computer vision section presents models like VGG-16, ResNet, and EfficientNet, which are pivotal in image recognition and classification tasks. The infographic demonstrates the interconnectedness of these technologies and their combined role in advancing AI applications.

# Part II: AI Data Product Description of ChatGPT
## 2.1 Introduction
ChatGPT is a language model that is trained by a lot of text data, allowing it to generate text based on the given input. It is best used as a chatbot or virtual assistant because it can understand and generate a wide range of responses in a human-like manner.
## 2.2 Use-case
The primary use-case of ChatGPT is natural language processing and understanding. It is designed to generate human-like text based on the input it receives, making it an effective tool for a wide range of applications that require text generation or human-computer interaction in natural language. 

### AI Problem ChatGPT Solves
ChatGPT addresses the challenge of generating coherent, context-aware, and relevant text in real-time. Traditional models struggled with maintaining context or producing text that feels "natural" to human readers. ChatGPT, with its deep learning architecture, can understand context, answer questions, generate content, and even mimic certain styles of writing, making it one of the most advanced language models available for tasks that involve human-like text generation.
## 2.3 Capabilities and Application Domain
ChatGPT's capabilities, grounded in natural language processing (NLP), enable it to understand, interpret, and respond to human language in a manner that closely resembles human interaction. Leveraging advanced machine learning and deep learning techniques, ChatGPT can process large volumes of text and voice data, learning from this data to improve its language models. The system is designed to perform a variety of NLP tasks, such as sentence parsing, word segmentation, stemming, lemmatization, and tokenization, which help in breaking down and comprehending text at a granular level.

In its application domain, ChatGPT applies these NLP capabilities to a range of functions, from conducting conversations with users in natural language to generating written content, answering questions, and even translating languages. The underlying technology includes statistical NLP, which uses algorithms combined with machine learning and neural networks like CNNs and RNNs, to not only understand and generate language but also to refine its accuracy and contextual relevance over time, thereby enhancing its interaction with users. (What is natural language processing? | IBM, z.d.)

## 2.4 Description of Data Product Components and Techniques
### 2.4.1 User-interface
The ChatGPT user interface has a text input box where users can input their questions, statements, or prompts. This is the primary method to interact with ChatGPT.  Once a query is submitted, the model’s response is displayed in this area. It looks like a chat, with alternating messages from the user and the model. On the left is a history of chats where the user can have multiple instances of a chat with their own context or prompt.
2.4.2 Agency and architecture
ChatGPT operates on a principle of artificial agency that is distinct from traditional intelligence. Its underlying structure, composed of LLMs like GPT-3, processes text by statistically analyzing the arrangement of data rather than grasping semantic meaning. These models do not engage in human-like cognition but can generate text that is often indistinguishable from that produced by humans, thanks to their predictive capabilities and pattern recognition derived from extensive training on internet-sourced datasets. (Floridi, 2023).

The agency exhibited by ChatGPT is marked by its capacity for human-like interaction, responding to prompts with a level of coherence that belies its lack of true understanding. Its neural network architecture, trained on a wide array of text, allows it to produce contextually appropriate responses. Moreover, ChatGPT showcases a novel form of agency that can adapt and refine its responses through reinforcement learning, all without the need for conventional intelligence. This decoupling of agency from intelligence presents a paradigm shift, prompting a reevaluation of action and interaction within the digital realm. (Wagh, 2023; Floridi, 2023).



### 2.4.3 Learning algorithm
The learning algorithm for the model is a structured process that begins with Supervised Fine-Tuning, where a pre-trained model from the GPT-3.5 series is further trained on a select dataset. This dataset, crafted by human workers from specific prompts, is designed to enhance the model's ability to generate relevant responses. The subsequent phase involves the Reward Model, where labelers rank the outputs of the fine-tuned model, creating a larger dataset that trains the reward model to evaluate the quality of responses.

Proximal Policy Optimization, a reinforcement learning method, is then applied to fine-tune the model's performance based on the reward model's rankings. This step is crucial for optimizing the model's responses to be more effective and appropriate. The model's success is gauged by its helpfulness, truthfulness, and harmlessness, which are central to its evaluation.

Despite the structured approach, the Reinforcement Learning from Human Feedback (RLHF) method faces challenges, such as the subjective nature of labeler preferences and the potential for non-representative training data. The goal is to align the model's outputs with human expectations, but this is complicated by the subjective and diverse nature of human preferences and the complexity of the training process. (Ramponi, 2023)
### 2.4.4 How is it trained?
ChatGPT, developed by OpenAI, has rapidly gained popularity since its inception, occasionally causing server overloads. Built on the foundation of OpenAI’s GPT-3.5, ChatGPT is a Large Language Model (LLM) that leverages a vast dataset from the internet to produce human-like textual responses. While the model incorporates user queries into its training, users have the option to opt-out. Central to its design is the transformer architecture. OpenAI fine-tuned GPT-3.5 for user interaction using a method called "Reinforcement Learning from Human Feedback" (RLHF). The process began with supervised fine-tuning, where trainers simulated human-AI conversations. This was followed by creating a reward model for reinforcement learning, wherein AI trainers graded generated responses. The model was then further refined using Proximal Policy Optimization. ChatGPT's data sources are diverse, including websites, books, and journals, and it utilizes natural language processing (NLP) to enable fluid interaction with humans. (Somoye, 2023)
### 2.4.5 ChatGPT Parameters
In the realm of AI, parameters determine an AI’s behavior and control its responses. One key parameter is "Temperature," which influences the "flavor" of the conversation: a higher temperature results in more adventurous and creative responses, while a lower one produces more conservative and predictable answers. Another vital parameter is "Max Tokens" or max_length, which controls the AI's verbosity. For instance, gpt-35-turbo has a limit of 4096 tokens, while gpt-4 variants have limits ranging from 8192 to 32768 tokens. This parameter can be adjusted to create brief or in-depth responses, depending on the user's preference. The "Diversity Penalty" ensures the AI's generated text remains engaging by penalizing repeated words. This penalty ranges from 0 to 2, with higher values producing more diverse output. (Onslow, 2023)
Part III: Use Case Description & Application
## 3.1 Popular Use-cases
ChatGPT has emerged as a versatile tool in the digital landscape, with applications that span from crafting engaging content for digital platforms to aiding in creative writing endeavors. Its ability to seamlessly translate languages makes it a valuable asset for global communication. In the sphere of customer interaction, ChatGPT powers chatbots capable of delivering human-like responses, enhancing the customer service experience and functioning as efficient personal virtual assistants.

In the technical domain, ChatGPT assists programmers by generating code for a variety of tasks, although with certain limitations in complexity and optimization. It streamlines the debugging process by identifying errors and proposing solutions, and it simplifies coding through its predictive completion features. Furthermore, ChatGPT contributes to code quality by recommending refactoring strategies to improve readability and performance, and it aids in the creation of clear documentation for better code maintenance. Additionally, it generates concise code snippets that serve as practical examples for specific programming tasks, demonstrating its utility in the coding process. These capabilities make ChatGPT an invaluable resource for a wide range of professional and creative applications.(Dilmegani, 2023)

## 3.2 Different ChatGPT Examples
### 3.2.1 Fact-checking/Truth finding

![Fact-checking example](/assets/fact-checking-example.png) \
In the realm of fact-checking or truth finding, Chat-GPT acts as a resourceful assistant due to its broad training on a multitude of facts and general knowledge. When confronted with questions like whether Holland is the capital of the Netherlands, Chat-GPT not only corrects the misconception by stating that Amsterdam is the capital, but also clarifies that Holland refers to two provinces within the country. This showcases the model's ability to grasp context and use it to provide clear and precise answers.
Chat-GPT's utility in fact-checking is enhanced through prompt engineering, where it can rephrase questions for better clarity or directly target the core of the inquiry. This technique ensures that the AI understands and addresses the query effectively.
Following Human-Computer Interaction principles, the tool is designed to be user-friendly, offering information in a conversational manner that's easy to understand and engage with, thus making complex information more accessible to a wider audience.
The performance and accuracy of Chat-GPT are central to its design, with a constant loop of user feedback and updates to the model to refine its responses. Adjustments to parameters like temperature and max tokens are made to balance the preciseness and conciseness of the answers, ensuring that users receive correct information without unnecessary complexity.
Overall, Chat-GPT's application in fact-checking serves as a bridge between users and information, simplifying the pursuit of truth and knowledge through a conversational and user-centric approach. (Hoes, Altay, & Bermeo, 2023)

### 3.2.2 Question answering

![Question-answering example](/assets/question-answering-example.png) \
Enhancing the question-answering abilities of ChatGPT involves the integration of embeddings, vector search, and prompt engineering. This approach seeks to mitigate the model's tendency to produce less reliable responses when faced with topics beyond its initial training data. By using embeddings, the text is converted into a semantically rich format that is more conducive to effective searchability. These embeddings are then stored in vector databases, which allow for their swift retrieval when needed.
The technique of prompt engineering is employed to direct ChatGPT towards delivering more accurate answers. This is achieved by first processing the data, then generating embeddings, and finally, creating well-crafted prompts that fuse the user's questions with related text snippets. Such prompts enable ChatGPT to provide responses that are both relevant and precise.
To facilitate the deployment of these strategies, Langchain, a Python package, is utilized to streamline the establishment of a question-answering system that is sensitive to the context of inquiries. By applying these methods, ChatGPT can be fine-tuned to cater to specific datasets, thereby greatly enhancing its effectiveness for a variety of natural language processing applications. (Brand, 2023)

### 3.2.3 Educational tutoring

![Educational-tutoring example](/assets/education-tutoring-example.png) \

Chat-GPT, as an advanced natural language processing model, is making significant strides in the educational sector by enhancing the learning experience through AI-driven conversations. It leverages deep learning to understand and generate text, creating interactive dialogues where students can ask questions and receive immediate feedback. This interaction promotes active learning and helps deepen students' understanding of subjects.

The model's ability to personalize learning experiences is particularly noteworthy. It analyzes individual learning patterns to provide tailored responses, making learning more effective and giving students a sense of control over their educational journey. For educators, Chat-GPT acts as an AI assistant, aiding in content creation, suggesting teaching strategies, and providing real-time feedback, thus reducing their workload and allowing them to concentrate on teaching.

Chat-GPT also supports inclusive education by offering various interaction methods, such as voice and text, catering to students with different learning needs. It fosters critical thinking by encouraging students to engage in discussions and debates, and it facilitates collaboration and knowledge sharing among students.

In practical applications, Chat-GPT serves as a virtual tutor, language learning aid, study companion for exam preparation, and a tool for interactive storytelling and gamification. It can also automate feedback and grading, as well as generate educational content, thereby transforming traditional educational practices.

In summary, Chat-GPT is at the vanguard of educational innovation, enhancing engagement, personalization, and inclusivity in learning. Its role is not to replace teachers but to augment the educational process, providing a supportive AI companion for students and educators alike. (Nakandakari, 2023)

### 3.2.4 Theory-of-mind problem solving

![Theory-of-mind example](/assets/theory-of-mind-example.png) \

Chat-GPT's recent achievement of solving 95% of theory of mind tasks is a significant milestone in the realm of artificial intelligence. Theory of mind (ToM) is the cognitive ability to understand that others have beliefs, desires, intentions, and perspectives that are different from one's own. It's a fundamental aspect of human social interaction, allowing us to empathize and predict others' behavior based on their mental states. This skill is crucial for effective communication and is developed in humans as they grow, often assessed through tests like the "Sally-Anne" task, which measures understanding of false beliefs.
In the context of AI, applying Chat-GPT to ToM problem-solving involves creating scenarios where the AI must infer the beliefs or intentions of characters in a given narrative, despite having different information itself. This is done through prompt engineering, where scenarios are constructed to elicit responses that reveal the AI's ability to understand and predict the mental states of these characters.
The interaction between Chat-GPT and users, in line with HCI principles, is designed to be intuitive, allowing the AI to engage in a seemingly empathetic dialogue. The performance and accuracy of Chat-GPT in these tasks are indicative of its sophisticated language processing capabilities and its ability to apply learned patterns to new, unseen situations.
The parameters for optimizing Chat-GPT's performance in ToM tasks are likely fine-tuned based on a range of interactions that simulate various social scenarios. This tuning enables the AI to better predict and respond to prompts that require an understanding of false beliefs or differing perspectives.
The significance of Chat-GPT's performance in ToM tasks lies not in the suggestion that the AI has achieved human consciousness, but rather in its ability to mimic a key component of human social cognition. While it's important to note that passing ToM tasks does not equate to actual understanding or consciousness, the rapid learning curve of AI models like Chat-GPT is noteworthy. In just a few years, AI has gone from having no capability in this area to performing at a level comparable to human children, showcasing the swift advancement and potential of AI cognitive development. (Nguyen, 2023)

### 3.4.5 APA-Style citation

![APA-style example](/assets/apa-style-example.png) \

When citing ChatGPT in APA style, the citation should reflect the AI's role as the information source, with OpenAI credited as the creator. The citation format in the reference list typically includes OpenAI as the author, the year, the title 'ChatGPT', the version, and the URL where the AI can be accessed. Prompt engineering and the AI's interaction with users are tailored to each use case, ensuring clear and relevant responses in line with HCI principles.
The performance and accuracy of ChatGPT's responses are contingent on the prompts given and its training. For academic purposes, the method of using ChatGPT should be detailed in the paper, and responses may be included in an appendix or supplemental materials. This allows for transparency in the research process and provides readers with access to the AI-generated content.
The APA style team has adapted citation guidelines for software to include AI models like ChatGPT, emphasizing the importance of consulting primary sources and maintaining academic integrity. These evolving guidelines aim to address the unique challenges posed by AI in academic writing, including issues of authorship and plagiarism. (McAdoo, z.d.)




# Part IV: Critical Reflection & Ethical Considerations
ChatGPT's rise in popularity was incredibly fast. Within just a few days, it seemed like everyone was talking about it, especially in tech circles. Many developers I know started to use it almost immediately. There's also a lot of investment flowing into AI from companies betting big on its future, which is creating many new jobs.

Public opinion on AI is really split down the middle. Some people are excited about AI, seeing it as a helpful tool that adds a lot of value to their work and daily life. But others are worried, especially about the possibility of AI taking over jobs humans currently do.

The impact of AI is huge; it's changing our lives in many ways, much like the coronavirus pandemic did. It's hard to imagine not having AI tools now, as they've become such a big help in work and everyday tasks.


## 4.1 Does ChatGPT help programmers?

It has been highlighted that ChatGPT is capable of writing useful code and excels at assisting with specific coding tasks, suggesting that it can be a significant aid for programmers looking to streamline their coding process or tackle routine coding tasks more efficiently.

Programmers can leverage ChatGPT to generate code snippets, explore libraries, and get assistance in breaking down complex projects into more manageable sub-tasks. This can potentially save time and resources, allowing programmers to focus on more complex aspects of software development that require a human touch and nuanced understanding.

However, the product also has its limitations. The text makes it clear that ChatGPT is not a replacement for human programmers, especially when it comes to constructing complete applications or handling tasks that require a deep and nuanced understanding of specific or complex problems. It also underscores the importance of programmers verifying the AI-generated code and not blindly trusting it, which means programmers still need to be deeply involved in the coding process, ensuring the reliability and correctness of the code.

In essence, while ChatGPT may not independently handle all aspects of programming, it serves as a robust support tool for programmers by taking on routine coding tasks, providing code examples, and assisting with research on coding libraries. It empowers programmers to be more efficient and effective in their work. (Gewirtz, 2023)

## 4.2 Potential Issues in relation to the European AI-act
Under the AI Act, AI systems are categorized by the level of risk they pose, which means that while ChatGPT-like models are generally considered low risk, their risk level could increase based on their application in critical sectors such as healthcare or finance, necessitating stricter regulatory compliance. These systems are also required to be transparent with users, indicating when an AI is in use, which would require ChatGPT to have clear labels or notifications during interaction. Moreover, there's a strong focus on preventing bias and discrimination; hence, developers must ensure that AI models do not perpetuate underlying biases from their training datasets.

In addition to bias mitigation, the AI Act would enforce data governance standards, ensuring that the data used for training AI models like ChatGPT complies with privacy laws and ethical guidelines. For high-risk applications, there would be stringent requirements for documentation and record-keeping related to datasets, training, and decision-making processes. Human oversight is another critical aspect, with the Act mandating mechanisms for human intervention in AI systems, allowing for corrections or overrides of AI decisions. Lastly, liability and accountability are addressed, raising questions about who bears responsibility for the outcomes of AI recommendations, a particularly pertinent issue for developers and users of AI systems like ChatGPT. OpenAI has already begun to address these concerns by documenting ChatGPT's development and engaging with the public on its educational applications, indicating a proactive approach to compliance with potential regulatory frameworks. (Aldabe et al., 2023)

# Part V: Studied Literature
## 5.1 ChatGPT Review by PCMag, 2023
The overview presents a comprehensive examination of ChatGPT, shedding light on its diverse functionalities and the breadth of its capabilities, while also acknowledging its constraints. It offers a balanced perspective by delineating both the strengths and weaknesses of ChatGPT right from the outset. In a comparative analysis, it juxtaposes ChatGPT with its contemporaries, such as Google Bard and Microsoft Bing Chat, delineating the areas where each platform excels or falls short. The review delves into the intricacies of how ChatGPT operates, its current applications, and its potential future roles, such as authoring content for platforms like Netflix. A notable aspect of the review is its attempt to objectively measure ChatGPT’s writing proficiency using the Flesch-Kincaid readability tests, which adds a quantitative dimension to the evaluation of the AI's linguistic prowess. (PCMag, 2023)

## 5.2 ChatGPT Review by Mollick (2022)
The review underscores a pivotal moment in the AI landscape, emphasizing ChatGPT's release as a monumental turning point that propelled AI from a niche tool to a versatile, ubiquitous resource with vast applications. It highlights the swift and exponential advancements in AI, with ChatGPT exemplifying the rapid growth in capabilities witnessed each year.
A notable highlight is the discussion of the profound productivity enhancement AI offers, particularly in domains like programming and writing, where AI can generate code and extensive text in multiple languages at remarkable speeds, revolutionizing these fields.

However, the review also addresses concerns regarding the potential misuse of AI, emphasizing the challenge of discerning truth from fiction as AI-generated content becomes increasingly convincing. It underscores the need to grapple with ethical and regulatory considerations to ensure responsible and beneficial AI deployment. Mollick (2022)

## 5.3 ChatGPT Review by Leggatt (2023)
The review highlights the remarkable surge in ChatGPT's popularity following its debut, acknowledging its distinctiveness in delivering engaging and precise conversations, and its capacity to furnish specific, informative responses.

It provides an insightful exploration of ChatGPT's operational mechanisms, elucidating its potential applications and distinguishing features from its predecessors in the AI model lineage. The review thoughtfully delineates the strengths and weaknesses of ChatGPT, acknowledging its proficiency in various domains while remaining mindful of its limitations, such as the knowledge cut-off and occasional output errors.

A notable aspect of the review is the practical testing of ChatGPT's capabilities, subjecting it to tasks such as explaining complex financial concepts and offering advice, providing a hands-on assessment of its real-world utility and performance. (Leggatt, 2023)
# References

1. Hoes, E., Altay, S., & Bermeo, J. (2023). Leveraging ChatGPT for Efficient Fact-Checking. Retrieved from https://psyarxiv.com
2. Aldabe, I., Farwell, A., Rigau, G., Rehm, G., & Way, A. (2023). Strategic plans and projects in language technology and artificial intelligence. In Cognitive technologies (pp. 361–386). https://doi.org/10.1007/978-3-031-28819-7_44
3. Brand, A. (2023, 2 mei). Using ChatGPT for question answering on your own data. Medium. https://medium.com/mlearning-ai/using-chatgpt-for-question-answering-on-your-own-data-afa33d82fbd0
4. Dilmegani, C. (2023, 1 oktober). 50 ChatGPT use cases in 2023. AIMultiple. https://research.aimultiple.com/chatgpt-use-cases/
5. Floridi, L. (2023). AI as agency without intelligence: on ChatGPT, large language models, and other generative models. Philosophy & Technology, 36(1). https://doi.org/10.1007/s13347-023-00621-y
6. Gewirtz, D. (2023, 3 oktober). How to use ChatGPT to write code. ZDNET. https://www.zdnet.com/article/how-to-use-chatgpt-to-write-code/
7. Leggatt, J. (2023, 7 september). What is ChatGPT? a review of the AI in its own words. Forbes Advisor Australia. https://www.forbes.com/advisor/au/business/software/what-is-chatgpt/
8. McAdoo, T. (z.d.). How to cite ChatGPT. https://apastyle.apa.org. https://apastyle.apa.org/blog/how-to-cite-chatgpt
9. Mollick, E. (2022, 14 december). ChatGPT is a tipping point for AI. Harvard Business Review. https://hbr.org/2022/12/chatgpt-is-a-tipping-point-for-ai
10. Nakandakari, F. (2023, 21 juli). Chat GPT in Education: Transforming Learning Experiences Through AI Conversations. Jestor. https://jestor.com/blog/a-i/chat-gpt-in-education-transforming-learning-experiences-through-ai-conversations/
11. Nguyen, T. T. T. (2023, 23 maart). ChatGPT achieves Theory of Mind - What does it mean? https://www.linkedin.com/pulse/chatgpt-achieves-theory-mind-what-does-mean-thanh-tuyen-tran-nguyen
12. Onslow, M. (2023, 5 mei). Understanding ChatGPT’s parameters: Getting started. Medium. https://medium.com/@mike_onslow/understanding-chatgpts-parameters-getting-started-32ec12b5e51b
13. Ortiz, S. (2023, 15 september). What is ChatGPT and why does it matter? Here’s what you need to know. ZDNET. https://www.zdnet.com/article/what-is-chatgpt-and-why-does-it-matter-heres-everything-you-need-to-know/
14. PCMag. (2023, 9 augustus). ChatGPT Review. PCMAG. https://www.pcmag.com/reviews/chatgpt
15. Ramponi, M. (2023, 4 augustus). How ChatGPT actually works. News, Tutorials, AI Research. https://www.assemblyai.com/blog/how-chatgpt-actually-works/
16. Reasoning in Artificial Intelligence - JavatPoint. (z.d.). www.javatpoint.com. https://www.javatpoint.com/reasoning-in-artificial-intelligence
17. Somoye, F. L. (2023, 1 september). How is Chat GPT trained? PC Guide. https://www.pcguide.com/apps/chat-gpt-trained/#:~:text=According%20to%20OpenAI%2C%20Chat%20GPT,user%20and%20an%20AI%20bot.
18. Team, A., & Team, A. (2023, 28 januari). ChatGPT and the future of Human-Computer Interaction. AIContentfy. https://aicontentfy.com/en/blog/chatgpt-and-future-of-human-computer-interaction#:~:text=ChatGPT%2C%20developed%20by%20OpenAI%2C%20is,a%20more%20human%2Dlike%20way.
19. Unleash the Power of ChatGPT: 11 epic prompt engineering tips! (z.d.). Colin Scotland. https://colinscotland.com/unleash-the-power-of-chatgpt-11-epic-prompt-engineering-tips/
20. Wagh, A. (2023, 2 juli). Architecture of OpenAI ChatGPT & Tips | Medium. Medium. https://medium.com/@amol-wagh/open-ai-understand-foundational-concepts-of-chatgpt-and-cool-stuff-you-can-explore-a7a77baf0ee3
21. What is artificial intelligence (AI) ? | IBM. (z.d.). https://www.ibm.com/topics/artificial-intelligence
22. What is natural language processing? | IBM. (z.d.). https://www.ibm.com/topics/natural-language-processing#:~:text=Natural%20language%20processing%20(NLP)%20refers,same%20way%20human%20beings%20can.
