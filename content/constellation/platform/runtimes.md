---
pcx_content_type: concept
title: Runtimes
weight: 20
---

# Constellation runtimes

Due to innovation in the AI space, there are various machine learning, AI tools and frameworks being improved or emerging. Constellation was designed to support multiple machine learning (ML) runtimes at its core.

Our vision is to support multiple runtimes over time. Currently, we only support the ONNX Runtime, but we are exploring and researching others. [XGBoost](https://xgboost.ai/) is in the final stages of testing.

| <div style="width:50px">Key</div> | Name | Description |
| ------- | ----- | -----|
| `ONNX` | ONNX Runtime | Cross-platform machine-learning model accelerator. ONNX Runtime can be used with converted models from PyTorch, Tensorflow/Keras, TFLite, scikit-learn, and other frameworks. |

Use Wrangler to list the models Cloudflare supports:

```bash
$ npx wrangler constellation runtime list

┌──────┐
│ name │
├──────┤
│ ONNX │
└──────┘
```

## Supported runtimes

### ONNX

Constellation supports the [ONNX Runtime](https://onnxruntime.ai/). The Open Neural Network Exchange (ONNX) is an ecosystem supported by multiple technology companies and research organizations, defines open standards for machine learning, and makes open-source software for AI.

The Open Neural Network Exchange (ONNX) is an ecosystem supported by multiple technology companies and research organizations. ONNX defines open standards for machine learning, and makes open-source software for AI.

The two essential parts of ONNX are the [open file format](https://onnx.ai/)), made with interoperability and [easy conversion](https://github.com/onnx/tutorials#converting-to-onnx-format) from other formats in mind, and the [ONNX Runtime](https://onnxruntime.ai/), which we are running in Constellation.

