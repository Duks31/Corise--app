![Logo](https://github.com/Duks31/Corise--app/blob/master/assets/corise_summarizer.png)

## The Problem
I'm a huge fan of podcasts and love the format as a way to gain deep insights into different industries & technologies and learn from the lived experience of people all over the world. But there is limited time and I end up listening to only some of them! I'm subscribed to several interesting podcasts that release 1-2 episodes a week and the problem is that it's hard to identify an episode that would appeal to me. While many episodes provide show notes, additional links and timestamps, I don't find them very helpful in truly understanding the unique aspects and making me want to listen to it! How can I make this discovery process more interesting and efficient?

## Solution
I would like to generate a personalized newsletter every week that summarizes each podcast episode released in that week. It would include information about the guest on the episode, the main topics discussed as well as some highlights. It would work by collecting a list of RSS feeds from the user and on a periodic basis, process the latest episodes and generate the newsletter. This acts as a round-up of the week, provides the user with the right level of detail that allows them to decide which of the episodes are appealing and must be listened to. 

## Approach
I divide the approach to building this product into three parts -

* Part 1: use a Large Language Model (LLM) from OpenAI to build the information extraction functionality paired with a Speech to Text model for transcribing the podcast
* Part 2: use a simple cloud deployment provider to easily convert the information extraction function to run on demand - this would be the app backend
* Part 3: use ChatGPT from OpenAI as your coding assistant to create and deploy a front-end that allows users to experience the end to end functionality

## Technology Used
* Python
* Streamlit
* OpenAI API
* Modular
