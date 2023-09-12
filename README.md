# MyWork_2022_2023
주식회사 포스로직 이미지 프로세싱 팀 연구원
2022.03.02 ~ 2023.07.21

![Moire3D](https://github.com/sangjunpark97/MyWork_2022_2023/assets/74389054/d7eed918-4115-4119-996e-2ace7126195d)

개발 알고리즘 Performance Table : [ImageProcessing_Algorithm_by_sangjunPark.pdf](https://github.com/sangjunpark97/MyWork_2022_2023/files/12582540/ImageProcessing_Algorithm_by_sangjunPark.pdf)

**기존 이미지 프로세싱과 딥 러닝을 결합해 모든 이미지 프로세싱 검사에 대한 요구를 한번에 해결하게 해주는 이미지 프로세싱 플랫폼 “FLImaging” 개발.**

- C/C++를 통한 인공신경망 프레임워크 연구/개발 및 이미지 프로세싱 알고리즘 연구/개발
- 각종 활성화 함수 최적화 구현, Tensor 연산 최적화 등등 라이브러리의 완성 및 최적화에 기여.
- 1인 작업으로, 3D Reconstruction (Moire, Multi-Focus, Laser-Triangulation), Object Detection (Optical-Flow), Image Filtering, Inpainting 등등 약 20개의 이미지 프로세싱 알고리즘을 개발.
- 각 알고리즘에 Multi-Threading, SIMD 병렬화 및 최적화 작업 진행.

### 사용 기술

---

- 언어 : C++ / C#
- Single, Multi Thread
- Naive, SIMD(SSE4, AVX2)

- ### ✍🏻개발 알고리즘

---

아래 알고리즘 모두 스스로 학습/연구를 통하여 개발.

🍀 3D Reconstruction

- Moire 3D
- Stereo Disparity
- Laser Triangulation (Image, Profile)
- Multi-Focus 3D

🍀 Calibrator

- Stereo Calibrator

🍀 Image Processing

- Inpainting Texture
- Mura Detection
- Thin Plate Spline Warping
- Optical Flow Polynomial Expansion
- Multi Focus
- Binomial Filter
- Gauss Filter
- Mean Curvature Flow Filter
- Mean Curvature Flow Weighted Filter
- Shock Filter
- High Dynamic Range
- Operation Power
- Page Pixel Picker
- Page Pooling
