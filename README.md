# TMDB-Crawl

https://www.themoviedb.org/ 사이트를 루비 & 레일즈 프레임워크를 통해 크롤링 하는 Task 입니다.

## 루비와 레일즈 설치하기
#### Rbenv를 통해 루비의 버전관리를 합니다. 
#### 본 루비 버전은 2.5.3, Rails 5.2.2.1 로 진행했습니다.

```
brew install rbenv ruby-build

#rbenv를 bash에 추가하기 
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile source ~/.bash_profile

#적용시키기
source ~/.bash_profile


#루비 버전 업데이트 (변경)
rbenv install 2.5.3
rbenv global 2.5.3
rbenv rehash


#레일즈 설치
gem install rails
```
