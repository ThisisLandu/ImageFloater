TODO: 
- 업데이트시 새버전 프로그램 실행 안되는것 해결
- 그리드 이미지 비율을, 가로세로 자동이 아니라  너비/높이에 맞춤별로 비율 지정

# ImageFloater

이미지를 화면 위에 띄워 자유롭게 조작할 수 있는 프로그램입니다.
지원 확장자 **[".png", ".jpg", ".jpeg",".jfif, ".bmp", ".heic", ".heif",".webp",".avif]**

### 이미지 폴더 관리

1. 우클릭 메뉴 → **폴더 관리** 선택
2. **폴더 추가** 버튼으로 이미지 폴더 추가
3. 그룹 생성으로 폴더들을 카테고리화 가능
4. 체크박스로 사용할 폴더/그룹 선택


## 주요 기능

- 폴더 그룹별 On/Off 관리 기능 **[F & O]**
- 항상 위에 표시 기능 **[F1]**
- 클릭 통과 모드 (이미지를 통해 아래 창 조작 가능) **[F2]**
- 이미지 확대/축소 및 이동 **[Ctrl+마우스 스크롤]**
- 투명도 조절 가능한 창에 이미지 표시 **[Shift+마우스 스크롤]**
- 이미지 그리드 표시 기능 **[G]**
- 이미지 비율 설정 기능
- 슬라이드쇼 기능
- 다양한 단축키 지원

## 사용 방법

### 기본 조작

- **상/하 화살표(↑, ↓) & (w, s) & 휠 스크롤**: 무작위 이전/다음 이미지 이동
- **좌/우 화살표(← , →) & (a, d) & PageUp/PageDown**: 이전/다음 이미지로 이동
- **Ctrl + 휠 스크롤**: 이미지 확대/축소
- **Ctrl + 마우스 드래그**: 이미지 이동
- **Alt + 휠 스크롤**: 투명도 조절
- **Esc**: 프로그램 종료
- **F11**: 창 전체화면
- **TAB**: 파일 경로 및, 이미지 해상도 확인
- **F & O**: 폴더 열기
- **R**: 폴더 리스트 새로고침
- **G**: 그리드 모드 전환(toggle)
- **F1**: 항상 위 기능 전환(toggle)
- **F2**: 클릭 통과 모드 전환(toggle)
- **T**: 상단 메뉴바 표시 전환(toggle)
- **Ctrl + Enter**: 현재파일 탐색기에서 열기
- **Ctrl + E**: 현재파일 그림판에서 열기
- **Ctrl + C**: 현재 이미지 클립보드에 복사
- **Del**: 현재파일 삭제
- **ESC**: 프로그램 종료 및 **설정 저장**


### 메뉴 기능

우클릭으로 컨텍스트 메뉴 표시:

- **항상 위에**: 다른 창보다 항상 위에 표시
- **투명도 조절**: 창의 투명도 설정
- **클릭 통과**: 클릭이 이미지를 통과하여 아래 창에 전달
- **화면 맞춤 모드**: 화면에 맞게/원본 크기/꽉 채움 등 설정
- **폴더 관리**: 이미지 폴더 추가/관리
- **슬라이드쇼**: 자동 이미지 전환 기능



### 슬라이드쇼 사용

1. 우클릭 메뉴 → **슬라이드쇼 시작** 선택 
2. 슬라이드쇼 간격은 우클릭 메뉴 → **슬라이드쇼 간격 설정**에서 조정

### 그리드 표시 모드

- 우클릭 메뉴 → **그리드 모드 사용** 선택
- 여러 이미지를 격자 형태로 한 번에 표시
- 그리드 임계값: 이미지 간 비율 차이가 클 때 그리드 표시 기준
- 그리드 크기 비율: 그리드 내 이미지 크기 조절


## 기술 정보

- 설정 파일: 프로그램 실행 파일과 동일한 경로에 `ImageFloater.ini` 생성
- 캐시 데이터베이스: `ImageFloater_cache.db` 파일에 스캔한 이미지 정보 저장
- Windows11 환경에서 동작 
---

# ImageFloater

A program that allows you to float images on the screen and manipulate them freely.
Supported extensions: **[".png", ".jpg", ".jpeg", ".jfif", ".bmp", ".heic", ".heif", ".webp", ".avif"]**

### Image Folder Management

1.  Right-click menu → Select **Folder Management**
2.  Add image folders using the **Add Folder** button
3.  Folders can be categorized by creating groups
4.  Select folders/groups to use via checkboxes

## Key Features

-   On/Off management function per folder group **[F & O]**
-   Always on Top feature **[F1]**
-   Click-Through Mode (Allows manipulating windows underneath the image) **[F2]**
-   Image zoom in/out **[Ctrl+Mouse Scroll]** and movement **[Ctrl+Mouse Drag]**
-   Adjustable window transparency **[Alt+Mouse Scroll]**
-   Image Grid display feature **[G]**
-   Image aspect ratio setting feature
-   Slideshow feature
-   Supports various hotkeys

## How to Use

### Basic Controls

-   **Up/Down Arrows (↑, ↓) & (W, S) & Mouse Wheel Scroll**: Move to random previous/next image
-   **Left/Right Arrows (←, →) & (A, D) & PageUp/PageDown**: Move to previous/next image
-   **Ctrl + Mouse Wheel Scroll**: Zoom image in/out
-   **Ctrl + Mouse Drag**: Pan/Move image
-   **Alt + Mouse Wheel Scroll**: Adjust transparency
-   **Esc**: Exit program and **save settings**
-   **F11**: Toggle fullscreen window
-   **TAB**: Check file path and image resolution
-   **F & O**: Open Folder Management
-   **R**: Refresh folder list
-   **G**: Toggle Grid Mode
-   **F1**: Toggle Always on Top
-   **F2**: Toggle Click-Through Mode
-   **T**: Toggle Top Menu Bar visibility
-   **Ctrl + Enter**: Open current file in Explorer
-   **Ctrl + E**: Open current file in Paint
-   **Ctrl + C**: Copy current image to clipboard
-   **Del**: Delete current file
-   **ESC**: Exit program and **save settings**

### Menu Functions

Right-click to display the context menu:

-   **Always on Top**: Keeps the window above other windows
-   **Adjust Transparency**: Set the window's transparency level
-   **Click-Through**: Clicks pass through the image to the window below
-   **Image Display Mode**: Set options like Fit to Screen / Original Size / Stretch to Fill, etc.
-   **Folder Management**: Add/Manage image folders
-   **Slideshow**: Automatic image transition feature

### Using Slideshow

1.  Right-click menu → Select **Start Slideshow**
2.  Adjust the slideshow interval via Right-click menu → **Set Slideshow Interval**

### Grid Display Mode

-   Right-click menu → Select **Use Grid Mode**
-   Displays multiple images in a grid layout simultaneously
-   **Grid Threshold**: Sets the tolerance for aspect ratio differences when displaying images in the grid.
-   **Grid Size Ratio**: Adjusts the size of images within the grid.

## Technical Information

-   **Settings File**: `ImageFloater.ini` is created in the same directory as the program executable.
-   **Cache Database**: Scanned image information is stored in the `ImageFloater_cache.db` file.
-   Runs on Windows 11 environment.
