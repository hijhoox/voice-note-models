# Voice Note models

Model files the Voice Note iOS app downloads. The app checks each file's SHA-256 before using it.

## ggml-large-v3-turbo-encoder.mlmodelc.zip

An 8-bit palettized Core ML encoder for Whisper large-v3-turbo, for use with whisper.cpp on the Apple Neural Engine.

- Release: `large-v3-turbo-encoder-8bit`
- Size: 570,709,613 bytes
- SHA-256: `5b06af945696ec364544e1c9633224f6c381a2ca89bebc61097011e8b16369c7`

This is an unchanged copy of the file from
[carl1758/meetnotes-models](https://huggingface.co/carl1758/meetnotes-models) at commit
`6f8698ba637138b4a9429cec07b2061b4ceb24ee`. That page describes how it was made: converted with whisper.cpp v1.9.3's
`convert-whisper-to-coreml.py`, then compressed with coremltools k-means palettization.

The Whisper weights are © OpenAI, released under the MIT License.

## License

MIT License

Copyright (c) 2022 OpenAI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
