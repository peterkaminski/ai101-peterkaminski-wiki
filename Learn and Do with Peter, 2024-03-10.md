# Learn and Do with Peter, 2024-03-10

YouTube: _link coming soon_

Notes: [[Learn and Do with Peter Notes, 2024-03-10]]

**Next:** _link coming soon_

**Previous:** [[Learn and Do with Peter, 2024-03-09]]

## Human Summary

We continued with "build our own alternative frontend to LLMs" with **Salamander**, and published a first, not-quite-ready-but-we-still-did-it version to GitHub as open source.

Along with some work with Salamander and discussing next steps in its development ("Salamander Roadmap"), some questions we covered:

- What went wrong yesterday writing code yesterday, and how did we fix it?
- How do local AI tools (LLMs, image generators) get model updates?
- Hugging Face is useful to whom?
- Quick look at a local LLM, llamafile
- Quick look at Stable Diffusion in Draw Things
- Who can get an OpenAI (or similar) API key? (anyone)
- Are there any gotchas (minimums, monthly fee) to OpenAI API pricing (no)
- What are some alternatives to GitHub? (GitLab, BitBucket, Codeberg, Gitea, Gitolite, Forgejo)

## AI Summary (hopefully useful, may be inaccurate)

### Quick Recap

Pete introduced HackMD and discussed effective naming of notes. The team considered creating an alternative front end for Chat GPT and acknowledged the responsibility of finding and fixing bugs. Pete demonstrated a working version of "Salamander," a program that interacts with Chat GPT via the command line, and discussed issues encountered with the front end of their program.

### Summary

**Salamander Project and API Key Issue**

Pete led a session on "Learn and Do" where he introduced a new note-taking tool and discussed effective naming of notes. The team discussed the possibility of creating an alternative front end for Chat GPT and acknowledged the responsibility of finding and fixing bugs. Pete demonstrated a working version of "Salamander," a program that interacts with Chat GPT via the command line. The team agreed to proceed with the Salamander project for the first half of the call, then switch to image-related topics for the second half. Pete also discussed issues encountered with the front end of their program, which was returning an error due to the use of an outdated API key. He resolved the issue by using a new API key and changing the way the program was calling the API. Pete also discussed the functionality of a chatbot, explaining its ability to respond to one question at a time. He also mentioned the potential for a more user-friendly interface and the need to develop a 'conversation' tool to simplify the process of juggling multiple text files. Finally, Pete hinted at something called the 'Roadmap' which they would be reviewing next.

**GUI, Terminal, and Wholesale Access Challenges**

Pete discussed the potential benefits of creating a graphical user interface (GUI) for their project, while acknowledging the challenges of setting it up and maintaining it. He emphasized the usefulness of learning the terminal interface, using the example of a tool called Lama file. Pete also discussed the benefits of gaining cheap wholesale access to LLMs through their own system, likening it to obtaining wholesale food. He also highlighted the challenges of this process, including additional responsibilities and potential difficulties. Pete then discussed the challenges he faced with a new system, particularly the documentation and naming conventions, and compared the system to a grocery store's loading dock. Despite these challenges, Pete managed to navigate the system successfully.

**OpenAI API Key Cost Discussion**

The team discussed the cost of using an API key with OpenAI. Pete clarified that there are no membership fees, minimum or maximum usage limits, or hidden costs. Users can set an upper limit on their usage. Pete also shared his experience with the API access mid-journey and compared OpenAI with other similar platforms like Anthropic. He reassured others that OpenAI wouldn't lose money on low-usage customers and confirmed that there is no limit for usage on OpenAI with your own front end.

**Development of Conversation Mode and Language Models**

Pete discussed the development of a conversation mode for their project, with the intention of maintaining a user-friendly chat style using 'me' and 'Chatbot'. He outlined the process of setting up this conversation mode, which involves writing the input and output files in a specific format. Pete also mentioned the possibility of setting up a web front end for a more user-friendly interface. He then explained the concept of language models, specifically the Llama File language model, which can be run locally on a computer. Pete also touched upon the topic of image generators and the potential use of the Draw Things app, which includes a language model, an image generator, and various post-processing tools.

**Image Generation and Language Models Explained**

Pete explained the workings of image generators and language models, highlighting their reliance on language for image generation. He clarified that stable diffusion is akin to a language model that can create images. Jeannie inquired about the necessity of internet connectivity for updates when running a local LLM. Pete responded that while the LLM doesn't automatically update, one can manually check for updates and switch to a newer version. He further explained that OpenAI uses a month and a day for version numbers and allows users to pick a nickname for their model. Pete concluded by suggesting that hugging face, a platform for AI developers, is primarily useful when creating or fine-tuning models, and that it isn't necessary unless one needs it.

**Github Utility and Open-Source Possibilities**

Pete discussed the utility and complexity of Github, highlighting its role in backups and collaborations. He demonstrated a simple use of Github and shared the idea of creating a web front end as an alternative. The next steps involved sharing the developed alternative front end and setting up an API key to access OpenAI. Pete also discussed the possibility of making their project open source and the concept of Github as a platform for sharing open-source code. Pete compared Github with Git Lab and expressed concerns about Microsoft's influence on open-source communities. He suggested the possibility of running locally-hosted versions of services like Github for privacy reasons.

**Open Source Project Discussion and Licensing Decisions**

Pete discussed his process of making a project open source and the importance of having a license file. He decided to copyright the project and establish himself as the owner while still providing users with certain permissions. He demonstrated how to set up a repository on Github and the potential of expanding the project to include image generation using OpenAI's API. The team agreed to focus on the conversation aspect of the project and Pete committed to announcing future meetings earlier in the week.