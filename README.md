<div align="center">

</div>

## QuizWiz

Outspeed is a PyTorch-inspired SDK for building real-time AI applications on voice and video input. It offers:

- Low-latency processing of streaming audio and video
- Intuitive API familiar to PyTorch users
- Flexible integration of custom AI models
- Tools for data preprocessing and model deployment

Ideal for developing voice assistants, video analytics, and other real-time AI applications processing audio-visual data.

## Install

You can install `outspeed` SDK from pypi using

```
pip install "outspeed[silero]>=0.1.143"
```

This would install the core `outspeed` package.
Read our [quickstart guide](https://docs.outspeed.com/examples/quickstart) to get started.

### Usage

Read the [docs](http://docs.outspeed.com) to learn more about the SDK.

To deploy your realtime function on Outspeed's infra, you can use the `outspeed deploy` CLI.

```
# functions.py contains your realtime function code
outspeed deploy --api-key=<your-api-key> functions.py
```

[Contact us](mailto:contact@outspeed.com) to get an API key and deploy.

Once deployed, you can use the playground in the examples repo to test the deployed code.

### Examples

All the examples are available in the `examples` folder.
To install the package so that all examples run, use:

```
pip install "outspeed[silero]>=0.1.143"
```

Or, if you're using poetry:

```
poetry add 'outspeed[silero]'
```

This will install all the additional libraries that are required for examples to work.

---

### Logging

To develop on top of the SDK, set environment variable `DEV_INFO` or `DEV_DEBUG` to get logs from the SDK for the corresponding log level.

## Roadmap

| Feature                                                      | Status     | Target Release |
| ------------------------------------------------------------ | ---------- | -------------- |
| Local STT                                                    | On the way | Q4 2024        |
| DeepReel Integration (Human Clone)                           | On the way | Q4 2024        |
| Long Conversation Support                                    | Planned    | Q4 2024        |
| Local Model Vision and Text (With Ollama, and vision models) | Planned    | Q4 2024        |
| Call Recording                                               | Planned    | Q4 2024        |
| Wakeup Word                                                  | Planned    | Q4 2024        |
| On device models                                             | Planned    | Q4 2024        |
| Local TTS                                                    | Planned    | Q4 2024        |

## Contribute

We welcome contributions to the Outspeed SDK! If you're interested in contributing, please submit a PR or [contact us](mailto:contact@outspeed.com).
