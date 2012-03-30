# 동기
-------

  리눅스에는 유명한 man 명령어가 있습니다. Node.js 에도 필요하지 않을까? 생각을 하자마자 프로젝트를 진행하기 시작했습니다.


# 문서작성 철학
---------------

  github에 README에 기재된 모든 내용보다는 필수적인 요소만 추출하고, 중요한 부분은 색상을 입혀서 작업시에 유용하게 참고할 수 있도록 작성해야 합니다.


# 문서추가 방법

- docs 디렉토리안에 <code>moduleName</code>_doc.js 규칙으로 생성되어야 합니다.
- 파일의 내용은

        exports.name = 'moduleName';                                                                                                                                                                                                               
        exports.context = 'use require';                                                                                                                                                                                         
        exports.homepage = 'http://homepage';                                                                                                                                                                                                   
        exports.description = [
        "\tblah blah"
        , "\tblh blah"
        ].join('\n');


  위와 같은 형식으로 작성하시면 됩니다.


