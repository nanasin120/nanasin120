# 프로젝트

## [MonoMirror](https://github.com/nanasin120/MonoMirror) 진행중
* **설명 :** 자기-지도학습 방식을 이용한 3D point cloud 생성 모델
* **주요 내용:**
    * DINOv2를 Encoder로 이용
    * RGB 재투영과 Feature 재투영 동시 이용
    * 대략 40장 정도의 이미지를 학습에 이용

### [3D_Voxel_Map_VoxFormer](https://github.com/nanasin120/3D_Voxel_Map_VoxFormer)
* **설명 :** VoxFormer논문을 바탕으로 이미지와 외부행렬, 내부 행렬만을 이용해 자동차 외부 환경을 3D Voxel로 생성
* **주요 내용:**
    * 가능성이 있는 복셀만을 Transformer에 사용해 연산량 감소
    * Transformer아키텍처를 이용한 정보 강화
    * Conv3d를 이용해 Transformer를 통해 얻은 복셀의 정보를 주위로 퍼트려 3D Voxel 맵 완성

# 개인 공부

### [CroCo](https://github.com/nanasin120/CroCo)
* **설명 :** CroCo논문을 바탕으로 자기-지도 학습을 통해 마스킹된 이미지 복원
* **주요 내용:**
    * 자기-지도 학습을 통해 마스킹된 이미지 복원 
    * 시점이 다른 이미지들을 Encoding함으로서 Encoder에는 이미지의 정보가 쌓이게 됨

### [Monodepth2](https://github.com/nanasin120/Monodepth2)
* **설명 :** Monodepth2논문을 바탕으로 자기-지도 학습을 통해 이미지의 깊이감 추정
* **주요 내용:**
    * 자기-지도 학습을 통해 정답지 없이 스스로 학습하는 모델 
    * 재투영을 통한 가상 이미지 생성
    * 부족한 데이터 증강

### [BEV-LSS-UNITY-PYTORCH](https://github.com/nanasin120/BEV-LSS-UNITY-PYTORCH)
* **설명:** LSS논문을 바탕으로 이미지와 외부행렬, 내부 행렬만을 이용해 자동차 외부 환경을 3D Voxel로 생성
* **주요 내용:**
     * 실시간 3D Voxel 생성
     * end-to-end 모델로 2차원 내용을 3차원으로 올리기
     * CrossEntropy와 DiceLoss를 이용해 IOU 개선

### [Car-Moving-DQN-Unity](https://github.com/nanasin120/car_moving_Unity_RL_DQN)
* **설명:** DQN을 이용해 벽이 부딫히지 않고 트랙을 따라 움직이는 자동차 학습
* **주요 내용:**
    * 유니티 mlagent환경 이해 및 보상 설정
    * DQN이해 및 구현

### [Deep Learning Paper Study](https://github.com/nanasin120/Deep-Learning-Paper-Study/blob/main/README.md)
* **Description:** 논문 보고 공부한 내용중 중요한 부분 간단하게 하려고 노력
    * non-local operation
    * Layer Normalization
    * Deep_Residual_Learning_for_Image_Recognition
### [LeNet-5-Pytorch](https://github.com/nanasin120/LeNet5-Pytorch-)
* **Description:** Yann LeCun의 1998년 논문 아키텍처를 원형 그대로 구현
* **Key Achievement:**
    * 모든 Feature map을 연결하지 않고 특정 map끼리만 연결하는 원본 논문의 연결 방식 재현

### [VGGNet-Pytorch: Research Paper Re-implementation](https://github.com/nanasin120/VGGNet-Pytorch)
* **Description:** Oxford VGGNet(A-E)의 모든 구성을 PyTorch로 충실히 구현
* **Key Achievement:**
    * 깊은 모델(VGG-D/E)의 **기울기 소실 문제를 Batch Normalization 도입으로 해결**
    * Learning Rate 스케줄링을 통한 학습 안정성 확보 및 성능 데이터 시각화
