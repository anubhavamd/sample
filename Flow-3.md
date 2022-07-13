```mermaid
flowchart LR
    TensorFlow-->Install-TensorFlow
    TensorFlow-->Test-TensorFlow
    TensorFlow-->Run-TensorFlow
    Install-TensorFlow-->Use-Docker 
    Install-TensorFlow-->Use-wheels-package
    Test-TensorFlow-->Test
    Run-TensorFlow-->Run
```
