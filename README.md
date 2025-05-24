from setuptools import setup, find_packages
setup(
    name='chatbot-telegram-bot',
    version='0.1.0',
    description='A Telegram bot that interacts with users using predefined intents and responses, and can also query GPT for additional responses.',
    author='Your Name',
    author_email='your.email@example.com',
    url='https://github.com/yourusername/chatbot-telegram-bot',  # Replace with your repository URL
    packages=find_packages(),
    install_requires=[
        'python-telegram-bot==20.0',  # Specify the version you are using
        'editdistance',
        'mistralai',
        'python-dotenv'
    ],
    classifiers=[
        'Programming Language :: Python :: 3',
        'License :: OSI Approved :: MIT License',
        'Operating System :: OS Independent',
    ],
    python_requires='>=3.6'
