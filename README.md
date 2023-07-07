# AI-Social-Story
This repo aims to create a bot that generates social story for autistic kids

# General Flow of the code
1. Receive as input the following details
   2. Childs name
   3. Social story context:
      4. Waiting in line
      5. Going to the bathroom alone
      6. Going abroad
      7. finishing kindergraden 
2. Go to "prompts folder" and send the proper prompts to ChatGPT over API
3. Create a social story based on the answers
4. Add proper images (should probably be static for now, i.e not AI generated)
5. Generate a PDF(or any other file) file with the story that the parent\professional can print\read out
6. All of the input should be flushed to keep the children privacy, no data should be stored anywhere


