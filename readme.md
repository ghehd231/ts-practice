# typescript 연습

> tsc --init
tsconfig.json 생성

* target: 컴파일된 코드가 어떤 환경에서 실행될 지 정의합니다.<br/> 예를들어서 화살표 함수를 사용하고 target 을 es5 로 한다면 일반 function 키워드를 사용하는 함수로 변환을 해줍니다. 하지만 이를 es6 로 설정한다면 화살표 함수를 그대로 유지해줍니다.<br/>
* module: 컴파일된 코드가 어던 모듈 시스템을 사용할지 정의합니다. <br/> 예를 들어서 이 값을 common 으로 하면 export default Sample 을 하게 됐을 때 컴파일 된 코드에서는 <br/>exports.default = helloWorld 로 변환해주지만 이 값을 es2015 로 하면 export default Sample 을 그대로 유지하게 됩니다.<br/>
* strict: 모든 타입 체킹 옵션을 활성화한다는 것을 의미합니다.<br/>
* esModuleInterop: commonjs 모듈 형태로 이루어진 파일을 es2015 모듈 형태로 불러올 수 있게 해줍니다<br/>

> tsc 명령어
tsc 명령어 입력시에 .ts 파일을 컴파일하여 .js파일로 변환에 생성해준다. <br/>
