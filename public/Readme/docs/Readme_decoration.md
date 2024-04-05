# Title troubles

- `markdown`에서 html과 css를 지원한다고 알고 있었지만, github는 보안 정책상의 이유로 `README.md` 등에 html과 css 사용 시 'washing'함.('GitHub’s focus on security is the reason for CSS restrictions')
- 원하는 애니메이션 효과를 `svg`파일을 만들어 구현하여 `github` 에서만 적용 가능한 방법으로 readme에 적용 ([Include an SVG (hosted on GitHub) in MarkDown](https://stackoverflow.com/questions/13808020/include-an-svg-hosted-on-github-in-markdown))해보았으나, 업로드하려는 파일의 경우엔 애니메이션과 google font가 들어가 `<style>`태그가 존재하고, svg 파일 자체에서 문제가 있어 제대로 upload되지 않음.
  - 관련 article: [Can I Use CSS In GitHub Markdown: Enhancing Your Readme Files](https://gadgetmates.com/github-markdown-css)   
- 정적인 부분은 png으로, 타이포라이트가 필요한 부분만 외부에서 svg를 만들어 전송하는 readme-typing-svg의 도움을 받았다.
