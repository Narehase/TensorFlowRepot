# TensorFlowRepot
> 현재의 TensorFlow 최신 버전은 >> 2.12.0 << 입니다.

최근들어 평소에 쓰던 TensorFlow GPU의 사용이 안되는 문제가 있습니다.
이유가 무엇일까요?

> TensorFlow 공식 사이트인 https://www.tensorflow.org/install/source_windows?hl=ko#tested_build_configurations 을 보면

```
참고: 기본 Windows에서 GPU 지원은 2.10 이하 버전에서만 사용할 수 있으며, TF 2.11부터는 CUDA 빌드가 Windows에서 지원되지 않습니다. Windows에서 TensorFlow GPU를 사용하려면 WSL2에서 TensorFlow를 빌드/설치하거나 TensorFlow-DirectML-Plugin과 함께 tensorflow-cpu를 사용해야 합니다.
```
라고 적혀 있습니다.

결국 GPU 학습을 위해서는 텐서 플로우 버전이 2.10.0 보다 작아야 합니다.


