# - 정규표현식

### 

> ## ^ : 문자열의 시작되는 표시
>
> ### $ : 문자열의 마지막을 표시
>
> > ##### Source - who is who
> >
> > ##### Regular Expression : ^who
> >
> > > Matches:	***<u>who</u>*** is who
> >
> > ##### Regular Expression : who$
> >
> > > Matches:	who is ***<u>who</u>***
>
> ### . : 와일드 카드와 비슷하며, 문자하나를 나눔 ... 일 경우 문자 3개씩 나눔
>
> > ##### Source - Regular expressions are powerFul!!!
> >
> > ##### Regular Expression : .
> >
> > > Matches:	***<u>Regular expressions are powerFul!!!</u>***
> >
> > ##### Regular Expression : ......  (. 이 6개 이므로 6개 단위로 문자열 끊고 6개로 안나누어지는 나머지는 버림)
> >
> > > Matches:	***<u>Regular expressions are powerf</u>***ul!!!
>
> ### \ : \ 뒤에 나오는 문자를 키워드가 아닌 문자로 인식하기위해 씀
>
> > ##### Source - O.K.
> >
> > ##### Regular Expression : \\.
> >
> > >Matches:	O***<u>.</u>***K***<u>.</u>***
> >
> > ##### Regular Expression : \\..\\.
> >
> > > Matches:	O***<u>.K.</u>***

