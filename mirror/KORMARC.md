본 항목은 [한국문헌자동화목록](%ED%95%9C%EA%B5%AD%EB%AC%B8%ED%97%8C%EC%9E%90%EB%8F%99%ED%99%94%EB%AA%A9%EB%A1%9D.md) 또는 [코마크](%EC%BD%94%EB%A7%88%ED%81%AC.md)로 검색해도
들어올 수 있습니다.  

![KORMARC.gif](//rv.wkcdn.net/http://rigvedawiki.net/r1/pds/KORMARC.gif)

[GIF image (13.88 KB)]

## Contents

    

1. KORMARC란? 
2. 설계원칙 
    

2.1. 형식의 범위

3. KORMARC 포맷의 특징 
    

3.1. USMARC와의 차이점

[[edit](http://rigvedawiki.net/r1/wiki.php/KORMARC?action=edit&section=1)]

## 1. KORMARC란? ¶

KORean MAchine Readable Cataloging

  

한국문헌자동화목록이라고도 하며, 축약어로는 코마크라고 한다.  
본래 [MARC](MARC.md)의 의미는 기계가독목록으로, 컴퓨터가 목록으로 작성된 레코드(Catalonging record)를
정보로 읽어 해석할수 있다는 것을 의미한다. 목록으로 작성된 레코드는 서지 레코드로서 전통적인 카드목록이 보여주는 정보와 동일하게 기술부,
표목부, 분류기호, 청구기호로 구성되어 있으며, 그 외에 MARC레코드에는 국제표준자료번호등 부가적인 정보를 수록 할 수 있다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/KORMARC?action=edit&section=2)]

## 2. 설계원칙 ¶

각종 자료에 대한 서지정보의 교환을 목적으로 도서관시스템간의 레코드 교환에 필요한 명세(specifcation)를 제공한다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/KORMARC?action=edit&section=3)]

### 2.1. 형식의 범위 ¶

본래 통합서지용 KORMARC 형식은 인쇄 또는 필사된 도서, 계속자료, 전자자료, 지도자료, 녹음자료, 시청각자료, 고서, 복합자료의
서지정보를 담을 수 있도록 설계되었다. 서지데어터에는 공통으로 자료의 표제, 저자명, 판사항, 발행사항, 형태사항, 주제, 주기에 대한
정보를 포함하고 있다. 자료의 형태에 따른 적용 서지형식은 다음과 같다.

  

  * **도서(BK)** : 단행자료의 특성을 가지고 있는 인쇄물, 필사본 그리고 마이크로자료  

  * **계속자료(CR)** : 종간을 예정하지 않고 시간을 두고 발행되는 서지적 자료. 계속자료에는 연속간행물(serial)과 계속갱신자료(ongoing integrating resources)가 포함된다.계속갱신자료는 분리되지 않은 채 추가되거나 갱신(updates)되는 자료와 전체 속에 통합되어 추가되거나 갱신되는 자료를 말한다. 통합되어 갱신되는 자료는 발행의 종간이 예정되었거나 예정되지 않을 수도 있으며, 여기에는 가제식자료와 갱신되는 웹사이트가 해당된다. 연속간행물(serial)은 연속하여 분리된 부분으로 계속해서 발행되는 자료를 말한다. 보통 종간을 예정하지 않고 권호표시를 지닌다. 연속간행물에는 연보, 계속 발행되는 명감(directory), 전자저널, 저널, 잡지, 단행자료의 시리즈물, 신문이 해당된다. 갱신되는 가제식자료(updating loose-leaf)는 페이지의 삽입이나 제거, 대체에 따라 갱신되는 하나 또는 여러 권으로 구성된 자료를 말한다.  

  * **전자자료(ER)** : 컴퓨터 소프트웨어, 수치데이터, 컴퓨터 의존형 멀티미디어, 온라인 시스템, 온라인 서비스 등 부호화된 전자 정보원이 해당된다. 자료의 특징은 단행자료 또는 연속간행물적인 특성을 가지고 있다.  

  * **지도자료(MP)** : 인쇄, 필사, 마이크로자료등 모든 형태의 지도로서 책자지도, 낱장지도, 구체(球體) 등이 포함된다. 자료는 단행자료, 연속간행물적인 특성을 가진다.  

  * **음악/녹음자료(ML)** : 인쇄, 필사, 마이크로 자료 등 모든 형태의 음악자료와 음악 외의 녹음자료가 포함된다. 자료는 단행자료나 연속 간행물적인 특성을 가진다.  

  * **시청각자료(VM)** : 평면영사자료, 평면비영사자료, 입체자료 및 실물자료와 키트를 포함한다. 자료는 단행자료, 연속간행물적인 특성을 갖는다.
  * **고서(RB)** : 대한제국 이전에 간인(刊印), 필사(筆寫)된 동장본(東裝本).  

  * **복합자료(MX)** : 주로 여러 형태가 혼합되어 수집된 문서나 필사자료에 적용한다. 대표적인 예로는 일괄문서처럼 의도적으로 수집된 컬렉션이라고 할 수 있다.  

[[edit](http://rigvedawiki.net/r1/wiki.php/KORMARC?action=edit&section=4)]

## 3. KORMARC 포맷의 특징 ¶

KORMARC 포맷의 설계의 중심원칙은 모든 유형의 자료에 대한 서지정보를 교환할 수 있도록 하는데 있으며, 통신을 목적으로 도서관시스템
사이의 레코드 교환에 필요한 명세(specification)를 제공하는데 있다. 본래 KORMARC포맷은 USMARC를 기본으로
작성되었는데,`[1]` 모든 국가별 MARC가 그렇듯이 KORMARC도 한국문헌의 특수성을 수용, 전개하고 있다. 한번 입력한 사항은 부출을
위하여 다시 입력하는 것을 배제하여 목록자의 데이터 입력 부담을 감소시키기 위하는 등 노력도 기울였다고 한다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/KORMARC?action=edit&section=5)]

### 3.1. USMARC와의 차이점 ¶

  * 한국의 대학별 간행물과 정부기관별 간행물을 코드에 의해 일괄검색 할 수 있도록 008필드에 한국대학부호(26~27)와 한국정부기관부호(/38~39)를 전개  

  * 한국, 중국의 옛 왕조명과 세계를 나타낼 수 있도록 개인명 표목 관련필드(100,600,700)에 식별기호(subfield code) $f(역조), $g(한국,중국의 세계)를 사용  

  * KORMARC포맷은 넓게 기술부와 검색부로 나뉘어지는데, 기술부는 한자가 포함된 데이터를 그대로 입력하고, 검색부 에는 한글,영문으로 입력하는 것을 원칙으로 하고 있다. 본서명(245필드의 $a), 총서명(440필드의 $a)의 경우에는 기술부에 위치하므로 한자가 그대로 입력되지만, 직접 검색용 색인이 작성 되므로 한글로 읽어 다시 부출하지는 않는다,.
  * 본 서명 앞에 나타나는 일반문구는 그 글자수에 따라 관칭(10자 미만), 관제(10자 이상)로 구분된다. 관칭의 경우에는 245필드(서명저자사항)의 본서명 앞에 원괄호로 묶어 기술되며, 제1지시기호에 의해 본서명만 부출할 것인지, 본서명과 관칭을 포함한 본서명을 함께 부출할 것이지 선택할 수 있도록 한다. 관제는 500필드에 기술한다.  

  * 서명관련 필드(130, 240, 245, 440, 730, 740)에서 알파벳 물자로 된 서명의 첫 머리에 검색시 배열에서 제외되어야 할 문자(The, A, An, La, Des)가 있는 경우에는 USMARC는 제1, 제2 지시기호에 제외된 글자수(0~9)를 입력하게 되어있으나, KORMARC에서는 관칭과 연계되어 있어 제2지시기호에 "1"을 입력하고 제외대상 단어를 서명 첫 머리에서 원괄호로 묶는다. 이것이 출력될시, 좌우의 원괄호는 생략되고 실제 데이터만 나타나도록 프로그램이 실행된다.  

  * 500필드(일반주기)의 식별기호를 서명 또는 저자관련 항목으로 전개하고, 입력한 데이터는 제1지시기호에 의해 직접 부출할수 있도록 되어 있다.  

  * 502필드(학위논문주기)의 식별기호를 학위논문사항($a), 학위수여기관($b), 학과 및 정공($c), 학위년도($d)등으로 구별하여, 필요시 학위논문을 학과,전공으로 검색할수 있도록 하였다.

`\----`

  * `[1]` 문헌정보의 국제유통을 감안한 것
