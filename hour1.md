Agenda:
What is generative AI?
How to use golang for AI?


What is generative AI?
AI model

Characteristics
    Learn from large dataset
    Produce similar but new output
    Can be applied to text, audo, images, video
        Produce different output.

Examples of Generative models:
    GPT: Generative pre-trained transformer  
        For generating text
    Dall-E:
        Generating images from textual description
    Music generation Models:
    Deep fakes & Voice Generation:

Problems solved by Generative AI:
    Content creation
    Data augumentation: Creating additional data for models to train
    Simulation and Modelling: for gaming, architecture or scientific research
    Personalization:
    Problem solving:

Various stages of Generative AI
    Data collection and Prep:
        Large dataset.
        Cleaned and formatted so that it can be used to train the model
    Model Design
        Design AI model architecture
            Choosing the type (ex: transformer model for text) and designing how it will learn the underlying pattern
            Architecture must understand the complexities of the data to generate similar but new outputs
    Training the model:
        Exposed to data repeateadly
        learing to predict the next item in a sequence (like next word in a text)
            Through a processs called backpropogation
                Here model adjusts its internal parameters based on difference in prediction and actual data.
        For text generation model learns the probability of a work appearing in a context in a sentence.
    Fine Tuning:
        Fine tuned for specific data or a particular task
            Example, genearating text on a particular style.
    Generation:
        For input, output is generated
        For text, model predicts the next word in a sequence, one word at a time. based on input on what it learned during training
    Iteration and Improvement:
        Outputs are evaluated
        further iterations of training and fine tuning

Why generative is better than discriminative models?
        Discriminative models -> good at classification and prediction by learning boundary between classes
        But generative model learn to understand and replicate the distribution of model itself.
    
------------------------
Golang and AI

Why
Performance and concurrency
Simplicity and efficiency
Libaries:
    GoLearn, Gorgonia, GoML, eaopt, Evo, and GoMind

Challenges:
Lack of high level libraries: 
    Not comparable with python
No Native bindings with CUDA
    For tasks such as deep learning No GPU binding unlike python
Deep learning curve:
    Go ecostystem from python maybe smaller

Libaries:
    GoLearn
    Gorgonia
    GoML
    eaopt
    Evo
    GoMind

