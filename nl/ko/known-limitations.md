---

copyright:
  years: 2017
lastupdated: "2017-09-10"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# 알려진 제한사항

다음 제한사항은 Akamai 벤더를 위한 새 CDN 서비스에 적용됩니다.
* HTTPS은 현재 와일드카드 인증서를 통해서만 지원됩니다.
* 디렉토리 레벨 컨텐츠 또는 다중 파일의 제거는 현재 지원되지 않습니다.
* 제공된 {{site.data.keyword.BluSoftlayer_notm}} 계정에 현재 허용된 CDN은 10개로 제한됩니다.
* 원본 및 TTL 항목의 총 수는 CDN당 75개로 제한됩니다.
* 시간이 경과된(stale) 컨텐츠 제공 옵션 기능은 이 옵션이 **해제** 상태로 CDN이 작성되었더라도 항상 **설정** 상태가 됩니다. 
* CDN이 **서버** 및 **HTTP 포트**와 함께 작성된 경우, 원본은 **서버** 옵션이 있어야 추가될 수 있습니다.
