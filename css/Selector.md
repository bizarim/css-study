1. 선택자
    1. 태그 선택자
    ``` html
    <style>
        h{color:red;}
    </style>
    <h>태그 선택자</h>
    ```
    1. 아이디 선택자
    ``` html
    <style>
        #select{color:red;}
    </style>
    <h id="select">아이디 선택자</h>
    ```
    1. 클래스 선택자
    ``` html
    <style>
        .select{color:red;}
    </style>
    <h class="select">클래스 선택자</h>
    ```
    1. 부모자식 선택자
    ``` html
    <style>
        ol > li{color:red}
        #select>li{color:red}
        ol,li{background:red}
    </style>
    ```
    1. 가상 선택자
    ``` html
    <style>
        a:hover{color:yellow;}
        a:active{color:green;}
        a:focus{color:white;}
    </style>
    <a href="">가상 선택자</a>
    ```