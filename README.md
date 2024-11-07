# GOT-OCR2-to-ONNX
convert GOT-OCR2.safetensors to onnx
I found the weight is safetensors when i git GOT-OCR2_0 from modelscope.But in order to deploy to Ascend servers, the model needs to be onnx so that i can proceed to the next step.Luckyly i find the solution.
references：
wangzhaode/llm-export: llm-export can export llm model to onnx. (github.com)
https://github.com/BaofengZan/GOT-OCRv2-onnx
https://modelscope.cn/models/stepfun-ai/GOT-OCR2_0/summary
