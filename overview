# EmaiLLM

EmaiLLM is a virtual co-worker that integrates with your email workflow. It can be CC’d or directly emailed for input and contextually aware responses. The goal is for EmaiLLM to provide helpful insights within long-running email threads, using memory and context management techniques to participate like a knowledgeable colleague.

## Features

- **Thread Context Awareness**: Keeps track of long-running email threads.
- **Memory Management**: Supports retrieval-augmented generation (RAG) or other memory frameworks to recall context from previous emails.
- **Flexible Email Integration**: Can be added to CCs or contacted directly, offering insights based on emails or requests.
- **Configurable Participation**: Users can adjust EmaiLLM’s involvement and style by sending feedback commands via email.
- **Style Matching**: Generates responses consistent with the tone and formality of the discussion, configurable by users.
- **Response Review**: Uses internal mechanisms inspired by GANs to self-evaluate and improve response quality.

## Installation

To set up and run EmaiLLM, follow these steps:

1. Clone the repository:
    ````bash
    git clone https://github.com/yourrepo/EmaiLLM.git
    cd EmaiLLM
    ````
2. Install required dependencies:
    ````bash
    pip install -r requirements.txt
    ````
3. Configure EmaiLLM with your preferred email server settings in `config.yaml`.

4. Start EmaiLLM:
    ````bash
    python emailgpt.py
    ````

## Configuration

EmaiLLM requires configuration for connecting to your email server. Modify the `config.yaml` file:

````yaml
email_server: smtp.mailprovider.com
email_port: 587
email_user: youremail@provider.com
email_password: yourpassword
response_style: conversational  # Options: 'formal', 'informal', 'conversational', etc.
participation_level: 3  # Scale from 1 (minimal) to 5 (very active)
````

You can also provide additional settings for response tuning, memory retention, and style matching directly via email feedback commands.

## Usage
To use EmaiLLM, simply add it to your email threads. Example:

````email
To: team@company.com
Cc: emailgpt@company.com
Subject: Scaling SMTP for the PaperclipMaximizer Project

Hi team,

Please provide input on scaling SMTP for our new project.

@EmaiLLM, could you find the RFC superseding RFC822 and analyze how it affects our DNS MX records configuration?

Thanks, looking forward to your responses.
````

EmaiLLM will analyze this email, retrieve context, and reply appropriately.

## Configuring Participation
You can configure how often or how detailed EmaiLLM's responses are via feedback commands. Simply email EmaiLLM with your feedback:

````email
To: emailgpt@company.com
Subject: Adjust Participation

Please reduce your participation level to 2 in this thread. Respond less frequently and focus on senior-level expertise.
````

EmaiLLM will adjust its settings accordingly.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
We welcome contributions! Please follow the standard process:

- Fork the repository.
- Create your feature branch (git checkout -b feature/my-feature).
- Commit your changes (git commit -am 'Add my feature').
- Push to the branch (git push origin feature/my-feature).
- Create a pull request.
