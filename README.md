# 프로젝트 소개

---

### [C#](https://github.com/junhun0106/CSharp)
  * [Memory Pool](https://github.com/junhun0106/CSharp/tree/main/MemoryPool)
    * DefaultMemoryPool(ArrayMemoryPool) vs SlabMemoryPool vs PinnedBlockMemoryPool  
  * [Parse](https://github.com/junhun0106/CSharp/tree/main/Parse)
    * .net version이 낮은 경우의 ReadOnlySpan<char> Parse 버전을 만들어보자 
  * [Span](https://github.com/junhun0106/CSharp/tree/main/Span)
    * Span 객체를 사용하여 string 혹은 string[]를 사용 할 때 성능을 확보해보자
  * [Trie](https://github.com/junhun0106/CSharp/tree/main/Trie)
    * Trie 알고리즘을 이용하여 string 필터에 성능을 확보해보자
  * [Study](https://github.com/junhun0106/CSharp/tree/main/StudyProject)
  * [벤치마크](https://github.com/junhun0106/CSharp-Benchmark)
    * Container, StringBuilder, Linq 등 각 종 벤치마크 프로젝트 모음
    * [Container Benchmark](https://github.com/junhun0106/CSharp-Benchmark/tree/main/Container)
      * BanchmarkDotNet 라이브러리를 이용하여 Container API, Linq에 성능 차이를 알아보자 
    * [StringBuilder](https://github.com/junhun0106/CSharp-Benchmark/tree/main/StringBuilder)
      * System.Text.StringBuilder vs ObjectPool(StringBuilderPool) vs ZString vs ValueStringBuilder

---

### Server(private)

* [ASP.NET CORE](https://github.com/junhun0106/CSharp/tree/main/ASPDOTNETCORE)
  * ASP.NET CORE 기초 프로젝트
  * [웹 서버 LatencyViewer](https://github.com/junhun0106/CSharp/tree/main/LatencyView)
    * Middleware와 View(Mvc)를 이용하여 Latency를 측정해보자
  * [Carter 라이브러리 사용](https://github.com/junhun0106/CSharp/tree/main/CarterModule)
    * DTO를 공용 프로젝트로 분리하여 클라이언트와 서버에서 Url 및 Method 관리를 용이하게 해보자
  * [gRPC](https://github.com/junhun0106/CSharp/tree/main/gRPCTestProjects)
    * gRPC 기초 프로젝트 및 **FailOver**
* [TCP 서버](https://github.com/junhun0106/CSharp/tree/main/TCPServer)
  * System.IO.Pipelines와 SocketAsyncEventAgrs를 이용하여 간단하 채팅 서버와 채팅 클라이언트를 만들어보자
  * System.IO.Pipelines를 최적화 해보자

### [DB](https://github.com/junhun0106/DB-REDIS)

#### MySql
* [DB FailOver](https://github.com/junhun0106/DB-REDIS/tree/main/DBFailOver)
  * DB에서 FailOver 시에 재시도 관련 테스트 코드
* [DB TestProject](https://github.com/junhun0106/DB-REDIS/tree/main/DBTest)
  * DB 테스트를 위한 기초 프로젝트
* [DB Wiki](https://github.com/junhun0106/DB-REDIS/wiki)
  * DB를 관리 시 유용한 팁 정리
    * Query 최적화
    * DB charset 버그
* [MySqlConnector](https://github.com/junhun0106/DB-REDIS/tree/main/Migration)
  * 여러 Coneector를 사용해보고, 빠르고 사용하기 쉬운 라이브러리를 찾아보자. 

### Redis(Private)
* 레디스를 이용한 세션 관리
* 레디스 마이그레이션 및 API 

---

### [C++](https://github.com/junhun0106/Cplusplus)

* [대학교 졸업작품 및 과제](https://github.com/junhun0106/Cplusplus/tree/main/University) 
