# present

We can put images 2 ways;

one, we can use markdown syntax

two, we can use html.

I will focus on markdown syntax

`![](path/to/your/image)`

This will do.

Using absolute path is not a good idea.

I have created a folder named `images` in my repo

Then I will write

`![](images/2018-12-29_08-56-07.png)`

This is the result :

![](images/2018-12-29_08-56-07.png)

I think this works fine for now..

## 크기 조절

https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown

`![](./pic/pic1s.png =250x)` 처럼,

`WIDTHxHEIGHT` 를 맞추어 주면 된다.

위의 예는 HEIGHT 를 생략한 것이다.

* 파일명 뒤에 한칸 띄라고 강조하셨다.

근데 사실 이렇게 해보니까 막상 깃허브페이지 자체에선 안 먹히는 걸 확인할 수 있었다 ㅠㅠ

위는 kramdown 문법이다.

## html 사용하기

`![](images/2018-12-29_08-56-07.png)`
대신

`<img src="path/to/image">`를 사용하고

이 경우

`<img src="images/2018-12-29_08-56-07.png">`

상대경로도 가능한데, 크기 조절도 가능하다.

<img src="images/2018-12-29_08-56-07.png" align="left" height="100" >
