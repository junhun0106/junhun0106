# 프로젝트 소개

* 간혹 업데이트되므로, 링크가 깨질 수 있음.

# Repositories

* 레포지토리 주요 프로젝트 및 라이브러리 소개   
---

### [C#](https://github.com/junhun0106/CSharp)
  * [Memory Pool](https://github.com/junhun0106/CSharp/tree/main/MemoryPool)
    * .NET 메모리풀들을 비교하고 Allocated와 성능이 뛰어난 메모리풀이 무엇인지 알아내보자
    * 매우 작은 byte는 고려하지 않는다.(작은 byte인 경우 'new byte[]'가 더 빠른 경우가 있을 수 있다.)
    * DefaultMemoryPool(ArrayMemoryPool) vs SlabMemoryPool vs PinnedBlockMemoryPool vs CustomArrayMemoryPool
  * [Parse](https://github.com/junhun0106/CSharp/tree/main/Parse)
    * .net version이 낮은 경우의 ReadOnlySpan<char> Parse 버전을 만들어보자 
  * [Span](https://github.com/junhun0106/CSharp/tree/main/Span)
    * Span 객체를 사용하여 string 혹은 string[]를 사용 할 때 성능을 확보해보자
  * [Trie](https://github.com/junhun0106/CSharp/tree/main/Trie)
    * Trie 알고리즘을 이용하여 string 필터에 성능을 확보해보자
  * PacketEncyption
    * 패킷(byte[]) 암호화(XOR 등)
   
 ### [C# Benchmark](https://github.com/junhun0106/CSharp-Benchmark)
 
* Container, StringBuilder, Linq 등 각 종 벤치마크 프로젝트 모음
  * 프로젝트가 분리 되어 있었으나(관리 소흘), 모두 하나로 합침
* [Container Benchmark]
  * BanchmarkDotNet 라이브러리를 이용하여 Container API, Linq에 성능 차이를 알아보자 
* [StringBuilder]
  * System.Text.StringBuilder vs ObjectPool(StringBuilderPool) vs ZString vs ValueStringBuilder
 
### [C# Proto](https://github.com/junhun0106/CSharp-Proto) 
 
* 완성되지 않았거나, 스터디 프로젝트 모음
* DotNetVerify
    * .NET 6 검증 프로젝트

---

### Server(private)

* [ASP.NET CORE]
  * ASP.NET CORE 기초 프로젝트
  * [웹 서버 LatencyViewer]
    * Middleware와 View(Mvc)를 이용하여 Latency를 측정해보자
  * [Carter 라이브러리 사용]
    * DTO를 공용 프로젝트로 분리하여 클라이언트와 서버에서 Url 및 Method 관리를 용이하게 해보자
  * [gRPC]
    * gRPC 기초 프로젝트 및 **FailOver**
* [TCP 서버]
  * System.IO.Pipelines와 SocketAsyncEventAgrs를 이용하여 간단하 채팅 서버와 채팅 클라이언트를 만들어보자
  * System.IO.Pipelines를 최적화 해보자
* [REST 서버]
  * HTTP 1.1 서버
  * 내가 직접 관리 할 수 있는 웹 서버를 만들어보자.
---
 
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

---
 
### Redis(Private)
* 레디스를 이용한 세션 관리
* 레디스 마이그레이션 및 API 

---

### Utilities(Private)
* 업무에 필요한 라이브러리 모음
* EmptyCollection
  * Array.Empty처럼 List.Empty, Dictionary.Empty를 사용 할 수 있도록 해보자
* ValueStringBuilder
  * Stack에서만 사용하는 StringBuilder.
---

### [C++](https://github.com/junhun0106/Cplusplus)

* [대학교 졸업작품 및 과제](https://github.com/junhun0106/Cplusplus/tree/main/University) 
* [Doodle]
 * 
 
---
 
### Flutter & Type Script

* 프로젝트만 파놓고 언제 공부할거니?
