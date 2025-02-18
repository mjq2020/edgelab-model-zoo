# SSCMA Model Zoo

<div align="center">
  <a href="https://sensecraftma.seeed.cc/" target="_blank"><img width="20%" src="https://sensecraftma.seeed.cc/images/SSCMA-Hero.png"></a>
</div>

English | [简体中文](README_zh_CN.md)

## Introduction

Welcome to SSCMA Model Zoo. We provide a series of pre-trained models for different application scenarios for you to use, with [SSCMA](https://github.com/Seeed-Studio/SSCMA), you can test or inference on these models and easily deploy them to edge computing devices.

SSCMA Model Zoo focuses on providing models trained on SSCMA optimized neural networks, which are tailored to real-world application scenarios and enable faster and more accurate inference on embedded devices.

## Application Scenarios

Currently, SSCMA Model Zoo provides pre-trained models for the following application scenarios:

{{model_list}}

If you need any pre-trained model for a specific dataset in a specific scenario, feel free to submit a feature request to [Issues](https://github.com/Seeed-Studio/sscma-model-zoo/issues/new/choose).

## Quickly Start

If you wish to use the model provided by SSCMA Model Zoo, we recommend that you follow the following steps:

1. Based on actual needs, select corresponding application scenario and choose appropriate neural networks. You can browse the test results that we provide for dicision.
2. Download the selected pre-trained model. For public pre-trained models, you can directly download them through the model link in the test results table.
3. Please refer to [SSCMA Documentation - Deployment Example](https://sensecraftma.seeed.cc/SSCMA/examples/examples) to deploy on edge computing devices. You can also use SSCMA to run our models on your computer, reproduce our test results or infer directly.

## Troubleshooting

If you encounter any problem with pre-trained models in SSCMA Model Zoo, we recommend that you first follow these steps to troubleshoot.

1. Check the correctness of the downloaded model. The end of the pre-trained model file name contains the SHA-1 hash of the model. You can calculate the SHA-1 of the downloaded model and compare it with the one in the model file name by yourself (e.g. using the `sha1sum` command under Linux) to check the model consistency.
2. Search [SSCMA Model Zoo - Issues](https://github.com/Seeed-Studio/sscma-model-zoo/issues) and [SSCMA - Issues](https://github.com/Seeed-Studio/SSCMA/issues) to see if there are other people who have the similar problem.

If none of the above methods help, or if you have other questions about SSCMA Model Zoo, please [Submit Issues](https://github.com/Seeed-Studio/sscma-model-zoo/issues/new/choose) to us.

## License

Different neural networks, datasets, and models are protected by different licenses, please refer to the [LICENSES](LICENSES) for detailed permissions and restrictions.
