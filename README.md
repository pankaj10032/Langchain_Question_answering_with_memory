Conversational memory is how chatbots can respond to our queries in a chat-like manner. It enables a coherent conversation, and without it, every query would be treated as an entirely independent input without considering past interactions.

The memory allows a "agent" to remember previous interactions with the user. By default, agents are stateless — meaning each incoming query is processed independently of other interactions. The only thing that exists for a stateless agent is the current input, nothing else.

There are many applications where remembering previous interactions is very important, such as chatbots. Conversational memory allows us to do that.

In this notebook we'll explore this form of memory in the context of the LangChain library.

We'll start by importing all of the libraries that we'll be using in this example.
