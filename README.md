![mnn-llm](resource/logo.png)

# mnn-llm
[![License](https://img.shields.io/github/license/wangzhaode/mnn-llm)](LICENSE.txt)
[![Download](https://img.shields.io/github/downloads/wangzhaode/mnn-llm/total)](https://github.com/wangzhaode/mnn-llm/releases)

[Read me in english ](./README_en.md)

## 模型支持

llm模型导出onnx模型请使用[llm-export](https://github.com/wangzhaode/llm-export)

当前支持以模型：

| model | onnx-fp32 | mnn-int4 |
|-------|-----------|----------|
| chatglm-6b | [![Download][download-chatglm-6b-onnx]][release-chatglm-6b-onnx] | [![Download][download-chatglm-6b-mnn]][release-chatglm-6b-mnn] |
| chatglm2-6b | [![Download][download-chatglm2-6b-onnx]][release-chatglm2-6b-onnx] | [![Download][download-chatglm2-6b-mnn]][release-chatglm2-6b-mnn] |
| chatglm3-6b | [![Download][download-chatglm3-6b-onnx]][release-chatglm3-6b-onnx] | [![Download][download-chatglm3-6b-mnn]][release-chatglm3-6b-mnn] |
| codegeex2-6b | [![Download][download-codegeex2-6b-onnx]][release-codegeex2-6b-onnx] | [![Download][download-codegeex2-6b-mnn]][release-codegeex2-6b-mnn] |
| Qwen-7B-Chat | [![Download][download-qwen-7b-chat-onnx]][release-qwen-7b-chat-onnx] | [![Download][download-qwen-7b-chat-mnn]][release-qwen-7b-chat-mnn] |
| Baichuan2-7B-Chat | [![Download][download-baichuan2-7b-chat-onnx]][release-baichuan2-7b-chat-onnx] | [![Download][download-baichuan2-7b-chat-mnn]][release-baichuan2-7b-chat-mnn] |
| Llama-2-7b-chat | [![Download][download-llama2-7b-chat-onnx]][release-llama2-7b-chat-onnx] | [![Download][download-llama2-7b-chat-mnn]][release-llama2-7b-chat-mnn] |

[download-chatglm-6b-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/chatglm-6b-onnx/total
[download-chatglm2-6b-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/chatglm2-6b-onnx/total
[download-chatglm3-6b-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/chatglm3-6b-onnx/total
[download-codegeex2-6b-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/codegeex2-6b-onnx/total
[download-qwen-7b-chat-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/qwen-7b-chat-onnx/total
[download-baichuan2-7b-chat-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/baichuan2-7b-chat-onnx/total
[download-llama2-7b-chat-onnx]: https://img.shields.io/github/downloads/wangzhaode/llm-export/llama2-7b-chat-onnx/total
[release-chatglm-6b-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/chatglm-6b-onnx
[release-chatglm2-6b-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/chatglm2-6b-onnx
[release-chatglm3-6b-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/chatglm3-6b-onnx
[release-codegeex2-6b-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/codegeex2-6b-onnx
[release-qwen-7b-chat-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/qwen-7b-chat-onnx
[release-baichuan2-7b-chat-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/baichuan2-7b-chat-onnx
[release-llama2-7b-chat-onnx]: https://github.com/wangzhaode/llm-export/releases/tag/llama2-7b-chat-onnx
[download-chatglm-6b-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/chatglm-6b-mnn/total
[download-chatglm2-6b-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/chatglm2-6b-mnn/total
[download-chatglm3-6b-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/chatglm3-6b-mnn/total
[download-codegeex2-6b-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/codegeex2-6b-mnn/total
[download-qwen-7b-chat-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/qwen-7b-chat-mnn/total
[download-baichuan2-7b-chat-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/baichuan2-7b-chat-mnn/total
[download-llama2-7b-chat-mnn]: https://img.shields.io/github/downloads/wangzhaode/mnn-llm/llama2-7b-chat-mnn/total
[release-chatglm-6b-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/chatglm-6b-mnn
[release-chatglm2-6b-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/chatglm2-6b-mnn
[release-chatglm3-6b-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/chatglm3-6b-mnn
[release-codegeex2-6b-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/codegeex2-6b-mnn
[release-qwen-7b-chat-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/qwen-7b-chat-mnn
[release-baichuan2-7b-chat-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/baichuan2-7b-chat-mnn
[release-llama2-7b-chat-mnn]: https://github.com/wangzhaode/mnn-llm/releases/tag/llama2-7b-chat-mnn

### 速度

| model             | android(f16/32)| macos (f32)   | linux (f32)    | windows (f32)  |
|:-----------------:|:--------------:|:-------------:|:--------------:|:--------------:|
| qwen-1.8b-int4    | 100.21 / 22.22 | 84.85 / 19.93 | 151.00 / 35.89 | 117.30 / 33.40 |
| qwen-1.8b-int8    |  99.95 / 16.94 | 67.70 / 13.45 | 118.51 / 24.90 |  97.19 / 22.76 |
| chatglm-6b-int4   |  17.37 /  6.69 | 19.79 /  6.10 |  34.05 / 10.82 |  30.73 / 10.63 |
| chatglm2-6b-int4  |  26.41 /  8.21 | 20.78 /  6.70 |  36.99 / 11.50 |  33.25 / 11.47 |
| chatglm3-6b-int4  |  26.24 /  7.94 | 19.67 /  6.67 |  37.33 / 11.92 |  33.61 / 11.21 |
| qwen-7b-int4      |  14.60 /  6.96 | 19.79 /  6.06 |  33.55 / 10.20 |  29.05 / 9.62  |
| baichuan2-7b-int4 |  13.87 /  6.08 | 17.21 /  6.10 |  30.11 / 10.87 |  26.31 / 9.84  |
| llama-2-7b-int4   |  17.98 /  5.17 | 19.72 /  5.06 |  34.47 /  9.29 |  28.66 / 8.90  |

- android
  - 测试设备: XiaoMi12
  -  处理器: Snapdragon 8gen1
  - 内存大小: 8 GB
- macos
  - 测试设备: MacBook Pro 2019
  -  处理器: Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz
  - 内存大小: 16 GB
- linux(wsl)/windows
  - 测试设备: PC
  -  处理器: Intel(R) Core(TM) i7-13700K @ 3.40 GHz
  - 内存大小: 32 GB
- CPU 4线程速度: prefill / decode `tok/s`


### 下载int4模型
```
# <model> like `chatglm-6b`
# linux/macos
./script/download_model.sh <model>

# windows
./script/download_model.ps1 <model>
```

## 构建

当前构建状态：

| System | Build Statud |
|:------:|:------------:|
| Linux | [![Build Status][pass-linux]][ci-linux] |
| Macos | [![Build Status][pass-macos]][ci-macos] |
| Windows | [![Build Status][pass-windows]][ci-windows] |
| Android | [![Build Status][pass-android]][ci-android] |

[pass-linux]: https://github.com/wangzhaode/mnn-llm/actions/workflows/linux.yml/badge.svg
[pass-macos]: https://github.com/wangzhaode/mnn-llm/actions/workflows/macos.yml/badge.svg
[pass-windows]: https://github.com/wangzhaode/mnn-llm/actions/workflows/windows.yml/badge.svg
[pass-android]: https://github.com/wangzhaode/mnn-llm/actions/workflows/android.yml/badge.svg
[ci-linux]: https://github.com/wangzhaode/mnn-llm/actions/workflows/linux.yml
[ci-macos]: https://github.com/wangzhaode/mnn-llm/actions/workflows/macos.yml
[ci-windows]: https://github.com/wangzhaode/mnn-llm/actions/workflows/windows.yml
[ci-android]: https://github.com/wangzhaode/mnn-llm/actions/workflows/android.yml

### 本地编译
```
# linux
./script/linux_build.sh

# macos
./script/macos_build.sh

# windows msvc
./script/windows_build.ps1

# android
./script/android_build.sh
```

默认使用`CPU`后端，如果使用其他后端，可以在脚本中添加`MNN`编译宏
- cuda: `-DMNN_CUDA=ON`
- opencl: `-DMNN_OPENCL=ON`


### 4. 执行

```bash
# linux/macos
./cli_demo # cli demo
./web_demo # web ui demo

# windows
.\Debug\cli_demo.exe
.\Debug\web_demo.exe

# android
adb push libs/*.so build/libllm.so build/cli_demo /data/local/tmp
adb push model_dir /data/local/tmp
adb shell "cd /data/local/tmp && export LD_LIBRARY_PATH=. && ./cli_demo -m model"
```


## Reference
- [chatglm-6b](https://huggingface.co/THUDM/chatglm-6b)
- [chatglm2-6b](https://huggingface.co/THUDM/chatglm2-6b)
- [codegeex2-6b](https://huggingface.co/THUDM/codegeex2-6b)
- [Baichuan2-7B-Chat](https://huggingface.co/baichuan-inc/Baichuan2-7B-Chat)
- [Qwen-7B-Chat](https://huggingface.co/tangger/Qwen-7B-Chat)
- [cpp-httplib](https://github.com/yhirose/cpp-httplib)
- [chatgpt-web](https://github.com/xqdoo00o/chatgpt-web)
- [cppjieba](https://github.com/yanyiwu/cppjieba)
- [ChatViewDemo](https://github.com/BrettFX/ChatViewDemo)
