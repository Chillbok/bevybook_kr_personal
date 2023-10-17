번역 원본 위치: [https://bevyengine.org/learn/book/getting-started/](https://bevyengine.org/learn/book/getting-started/)
# 시작 (Getting Started)

This section will help you get started on your Bevy journey as quickly as possible. 
It will walk you through setting up your development environment and writing a simple Bevy app.  
이 부분에서는 당신과 Bevy와의 여정을 가능한 한 빨리 시작할 수 있도록 도울 것입니다.
이것은 당신이 개발 환경을 구성하고 간단한 Bevy 앱을 작성하는 것을 안내할 것입니다.

## 빠른 시작 (Quick Start)

If you want to dive in immediately and you already have a working Rust setup, feel free to follow this "quick start" guide.
Otherwise, move on to the next page.  
만약 당신이 즉시 참여하고 싶고, 실제로 작동하는 Rust 구성이 있다면, 자유롭게 이 “빠른 시작” 가이드를 따르세요.
아니면, 다음 페이지로 이동하세요.

Note: the "fast compiles" setup is on the next page, so you might want to read that section first.  
주의: “빠른 컴파일” 설정에 대한 내용은 다음 페이지에 있으므로, 당신은 아마 그 부분을 먼저 읽는 것을 원할 지도 모릅니다.

### 예제 시도하기 (Try the Examples)
1. Clone the [Bevy repo](https://github.com/bevyengine/bevy):  
	[Bevy 저장소](https://github.com/bevyengine/bevy)를 복사:
	```bash
	git clone https://github.com/bevyengine/bevy
	```
2. Navigate to the new "bevy" folder:  
	새로 생긴 “bevy" 폴더로 이동:
	```bash
	cd bevy
	```
3. Switch to the correct Bevy version (as the default is the git main development branch)  
	올바른 Bevy 버전으로 전환 (기본적으로 설정되어 있는 버전은 git main 개발용 branch입니다)
	```bash
	# use the latest Bevy release
	# 가장 오래된 Bevy 배포판 사용하기
	git checkout latest
	
	# or a specific version
	# 또는 특정한 버전 사용하기
	git checkout v0.11.0
	```
4. Try the examples in the [examples folder](https://github.com/bevyengine/bevy/tree/latest/examples#examples)  
	[예제 폴더](https://github.com/bevyengine/bevy/tree/latest/examples#examples)에 있는 예제 시도해보기
	```bash
	cargo run --example breakout
	```

### Bevy를 종속성으로서 추가하기 (Add Bevy as a Dependency)