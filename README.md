# TA_Tool
# Roadmap

 16-bit PNG / EXR 출력 지원 (8bit로는 종종 디테일 손실)
 True gradient noise (Perlin) 구현 추가
 Normal Map: Tangent space ↔ Object space 변환
 Channel Packer: 회사별 프리셋 (Unity URP, Unreal ORM, Godot)
 Batch processing CLI 모드
 Blender 플러그인 버전


# Tech Stack

Python 3.10+
NumPy — 핵심 텐서 연산
Pillow — 이미지 I/O 및 리사이즈
SciPy — Sobel 필터, Gaussian blur
Gradio — 웹 UI


# References

Real-Time Rendering, 4th Ed. — Akenine-Möller, Haines, Hoffman et al.
The Book of Shaders — https://thebookofshaders.com
ambientCG (free PBR textures, CC0) — https://ambientcg.com
Catlike Coding shader tutorials — https://catlikecoding.com/unity/tutorials/


# License
MIT — 자유 사용. 학습 / 개인 프로젝트 / 상업적 사용 모두 허용.


Technical Artist 지망생이 게임 그래픽 파이프라인의 본질을 코드로 이해하기 위해 만든 학습 프로젝트

TA들이 다루는 이미지 필터와 픽셀에 대한 이해를 공부하기 위해 ai를 통해 코드를 작성
