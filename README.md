# free-webfonts
무료 한글 폰트는 많지만 웹폰트로 쓸 수 있는 공식적인 url이 항상 있는 것은 아닙니다. 항상 그 자리를 지키고 있어서 믿고 쓸 수 있는 웹폰트 url을 함께 만들어 봅시다. ~~사실 [프로젝트 눈누](http://noonnu.cc/) 같은 좋은 서비스가 있지만 갑자기 터질 수도 있으니 백업으로 하나 만들어둡시다.~~



## Contributing

새로운 폰트는 언제나 환영이야!

폰트를 추가할 때는 다음 사항들을 함께 수정해주세요.

#### font files

`.woff`, `.ttf` 등의 폰트파일들을 폰트마다 별도의 폴더를 만들어 그 안에 올려주세요.

#### css file

폰트 폴더 내에 다음 예시처럼 css파일을 하나 만들어서 사용시 간편하게 한 번에 import할 수 있도록 해주세요.

```css
@font-face {
    font-family: BusanBada;
    font-style: normal;
    font-weight: normal;
    src: 
      local('BusanBada'), 
      url(https://raw.githubusercontent.com/3jin/free-webfonts/master/BusanBada/BusanBada.woff) format('woff'), 
      url(https://raw.githubusercontent.com/3jin/free-webfonts/master/BusanBada/BusanBada.ttf) format('ttf');
}
```

#### README.md

폰트를 추가할 때는 README.md의 **Fonts** 항목을 함께 수정해주시고, 수정시에는 다음 내용들을 꼭 포함시켜주세요.
* 라이센스
  * 배포를 허용한다는 내용을 담고 있는 인용구를 찾아 써주세요.
  * 전문이 명시되어 있는 링크를 찾아 넣어주세요.
* 홈페이지

* 기타 주의사항이 있으면 '기타' 항목을 추가하셔서 써주시면 됩니다.



## Usage

#### 사용

css, sass, scss, less 등 사용하시는 css파일에 다음과 같이 필요한 폰트의 css파일을 임포트해주시면 됩니다.

```css
@import url('https://raw.githubusercontent.com/3jin/free-webfonts/master/BusanBada/BusanBada.css')
```



## Fonts

### BusanBada

* 라이센스

  > 1. 본 글꼴, 부산바다체의 저작권 일체는 남승우 개발자가 소유하고 있습니다. 저작권 및 지적 소유권은 대한민국 저작권법과 국제 저작권 협약에 의해 보호받습니다.
  > 2. 부산바다체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 수정하고 재배포할 수 있습니다.

  [전문](http://media.wix.com/ugd/3f3673_3ab1afd175814bd481fd3ad1d1d74935.pdf)

* 홈페이지

  [http://www.busanbadattf.com/](http://www.busanbadattf.com/)

* 기타

  * 홈페이지가 터져버렸다고 합니다.
  * 폰트의 ascender line과 base line이 폰트 크기의 50%만큼씩 위로 올라가 있으므로 사용시 보정이 필요합니다.