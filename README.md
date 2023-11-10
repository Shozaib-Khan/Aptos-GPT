# Aptos-GPT
A GPT-like LLM trained on the data provided by the Aptos Docs, Whitepaper, and the Move book by Damir Shamanaev

# Why
New Developers, especially devs like me who are also students, often struggle with getting even the smallest of questions answered, due to which they have to dig through 
community feeds or docs and find out what exactly they're looking for. This can be very tiring and frustrating, which often results in people losing their patience and calling it quits.
This DApp when realized with all the intended features, can provide great help to all the community members and the newbies to start their journey with Aptos.

# Current-Version
It is a simple Python Script that uses the OpenAI API key to crawl through the documents mentioned above and give responses to some entry-level questions, such as 
What is Aptos? What are its benefits, and what makes it different from existing blockchains like Ethereum and Solana. Using the Data it already has till 2021, this program 
can provide comparisons with other blockchains, perform debugging on snippets of Move code, and even present solutions to some problems in the programming of Movejus like Chat-GPT does.

# How It Works
I have used the LangChain document loader and provided all the information in .txt format to make it easier and more efficient to crawl through, find information, and provide the answers.
It uses the OpenAI API to perform all these actions.

# Future Vision
I intend to rely less on the OpenAi API to make it cheaper and much more private. It can be done by Collecting data from all the platforms where Aptos has a footing, such as Twitter 
and reports from events Aptos organizes, existing Move smart contracts, and much more, and using all those data to write a sophisticated Algorithm that I have more control over 
and then using a fine-tuned LLM over it to make the process smoother, faster, and much more attractive on the user side.
Using all the above data, the DApp will be able to take on large-scale problems and provide solutions at a rapid pace. With real-time data being fed to the databases, the world of Aptos 
evolves, this DApp can be a great starting point for all new aspiring developers trying to get into the Aptos blockchain.
Unfortunately, as of now, I neither have the skills nor the knowledge to do all of this but I intend to work on acquiring the necessary knowledge to 
complete this project and deploy it as soon as I can.
