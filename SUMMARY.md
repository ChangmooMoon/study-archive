# Table of contents

* [framework, library](README.md)
  * [Spring core](framework-library/spring-core/README.md)
    * [스프링 트라이앵글 - POJO, IOC/DI, AOP, PSA](framework-library/spring-core/pojo-ioc-di-aop-psa.md)
    * [Servlet](framework-library/spring-core/servlet.md)
  * [Spring MVC](framework-library/spring-mvc.md)
    * [DispatcherServlet](framework-library/spring-core/dispatcherservlet.md)
    * [Validation](framework-library/spring-mvc/validation.md)
  * [Spring Boot](framework-library/spring-boot.md)
  * [Spring Security](framework-library/spring-security.md)
  * [Spring Batch](framework-library/spring-batch.md)
  * [Spring Webflux](framework-library/spring-webflux.md)
  * [JPA](framework-library/jpa.md)
  * [JUnit, Spring Test](framework-library/junit-spring-test.md)
  * [etc](framework-library/etc/README.md)
    * [Slf4j MDC(Mapped Diagnostic Context)](framework-library/etc/slf4j-mdc-mapped-diagnostic-context.md)

## ETC, 개발 팁들

* [개발 팁들](etc/undefined.md)
  * [스프링 프로젝트 init 시에 해야될 것들](etc/undefined/init.md)
  * [vim 한글 깨질 때 인코딩 방식 지정](etc/undefined/vim.md)
  * [EC2 ssh connection 쉽게 하기](etc/undefined/ec2-ssh-connection.md)
  * [리눅스 커맨드, netstats](etc/undefined/netstats.md)
  * [Fork한 레포지토리 origin 업데이트](etc/undefined/fork-origin.md)
  * [git merge, rebase](etc/undefined/git-merge-rebase.md)
  * [Intellij 자주 쓰는 기능 단축키](etc/undefined/intellij.md)
  * [JSON handling](etc/undefined/json-handling.md)
  * [aws user-data.sh](etc/undefined/aws-user-data.sh.md)
* [Lombok annotation, 권장 방식](spring-framework-ecosystem/etc/lombok-annotation.md)
* [DB 모델링 시에 인조 식별자 정의하는 케이스](etc/db.md)
* [Redis pub/sub vs Apache kafka](etc/redis-pub-sub-vs-apache-kafka.md)

## Language

* [Java](language/java/README.md)
  * [자바 버젼별 feature](language/java/feature.md)
  * [JVM architecture](language/java/jvm-architecture.md)
  * [Garbage collection](language/java/garbage-collection.md)
  * [Java String pool](language/java/java-string-pool.md)
  * [java 8 Concurrent](language/java/java-8-concurrent.md)
  * [Optional](language/java/optional.md)
  * [Stream](language/java/stream.md)
  * [Comparator, Comparator](language/java/comparator-comparator.md)
  * [Error, Exception](language/java/error-exception.md)
  * [Java의 Call by value(pass by value)](language/java/java-call-by-value-pass-by-value.md)
  * [Java 변수 간 값 Swap 방식 5가지](language/java/java-swap-5.md)
* [Javascript](language/javascript.md)
  * [자주 쓰는 ES6 문법 정리](language/javascript/es6.md)
  * [ES6 module](language/javascript/es6-module.md)
  * [ES6 proxy](language/javascript/es6-proxy.md)
  * [scope, var closure 이슈, let, const](language/javascript/scope-var-closure-let-const.md)
* [Python](language/python.md)
  * [@lru\_cache](language/python/lru\_cache.md)

## CS

* [OS](cs/os/README.md)
  * [Process, Thread](cs/os/process-thread.md)
  * [CPU scheduling](cs/os/cpu-scheduling.md)
  * [sync vs async, blocking vs nonblocking](cs/os/sync-vs-async-blocking-vs-nonblocking.md)
  * [Memory segmentation](cs/os/memory-segmentation.md)
  * [virtual memory](cs/os/virtual-memory.md)
  * [페이지 교체 알고리즘](cs/os/undefined.md)
* [Network](cs/network/README.md)
  * [UDP](cs/network/udp.md)
  * [TCP](cs/network/tcp.md)
  * [DNS](cs/network/dns.md)
  * [HTTP](cs/network/http.md)
  * [web server, WAS](cs/network/web-server-was.md)
  * [Proxy, Load balancer](cs/network/proxy-load-balancer.md)
  * [web socket, WebRTC](cs/network/web-socket-webrtc.md)
  * [gRPC](cs/network/grpc.md)
  * [web secure](cs/network/web-secure.md)
* [DB](cs/db/README.md)
  * [MySQL](language/mysql.md)
  * [index](cs/db/index.md)
  * [정규화](cs/db/undefined.md)
  * [DB 트랜잭션, 동시성 제어 문제](cs/db/db.md)
  * [클러스터링](cs/db/undefined-1.md)
  * [레플리케이션](cs/db/undefined-2.md)
  * [샤딩](cs/db/undefined-3.md)
* [Data Structure, Algorithm](cs/algorithm/README.md)
  * [AVL tree, Red black tree](cs/algorithm/avl-tree-red-black-tree.md)
  * [B-tree, B\*tree, B+tree](cs/algorithm/b-tree-b-tree-b+tree.md)
  * [Hash](cs/algorithm/hash.md)
* [Design pattern](cs/design-pattern/README.md)
  * [SOLID](cs/design-pattern/solid.md)
  * [생성 패턴](cs/design-pattern/undefined.md)
    * [싱글톤 패턴](cs/design-pattern/undefined/undefined.md)
    * [팩토리 메서드 패턴](cs/design-pattern/undefined/undefined-1.md)
    * [빌더 패턴](cs/design-pattern/undefined/undefined-2.md)
    * [Null 객체 패턴](cs/design-pattern/undefined/null.md)
  * [구조 패턴](cs/design-pattern/undefined-1.md)
    * [퍼사드 패턴](cs/design-pattern/undefined-1/undefined.md)
    * [프록시 패턴](cs/design-pattern/undefined-1/undefined-1.md)
    * [어댑터 패턴](cs/design-pattern/undefined-1/undefined-2.md)
    * [데코레이터 패턴](cs/design-pattern/undefined-1/undefined-3.md)
  * [행위 패턴](cs/design-pattern/undefined-2.md)
    * [전략 패턴](cs/design-pattern/undefined-2/undefined.md)
    * [템플릿 메서드 패턴](cs/design-pattern/undefined-2/undefined-1.md)
    * [상태 패턴](cs/design-pattern/undefined-2/undefined-2.md)
    * [옵저버 패턴](cs/design-pattern/undefined-2/undefined-3.md)

## 소프트웨어 아키텍쳐

* [Layered Architecture](undefined/layered-architecture.md)
* [클린 아키텍쳐](undefined/undefined.md)
* [DDD](undefined/ddd.md)
* [etc](undefined/etc/README.md)
  * [DTO vs VO](undefined/etc/dto-vs-vo.md)

## 개발 서적들

* [소트웍스 앤솔로지에서 소개되는 객체지향 생활 체조 원칙 간략 정리](undefined-1/undefined.md)
* [엘레강트 오브젝트 - 새로운 관점에서 바라본 객체지향](undefined-1/undefined-1.md)
* [만들면서 배우는 클린 아키텍쳐](undefined-1/undefined-2.md)

***

* [테크 블로그](undefined-2.md)
