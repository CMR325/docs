---
ms.openlocfilehash: dcb31ab7b27f6f3ebe89699a3a2e96dd1e78a5db
ms.sourcegitcommit: 872c4751a3fc255671295a5dea6a2081c66b7b71
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/30/2022
ms.locfileid: "145067992"
---
{% data reusables.enterprise-accounts.access-enterprise %} {% data reusables.enterprise-accounts.policies-tab %} {% data reusables.enterprise-accounts.actions-tab %} {%- ifversion ghec or ghes > 3.3 or ghae-issue-5091 %} {% data reusables.enterprise-accounts.actions-runner-groups-tab %}
1. **새 실행기 그룹** 을 클릭합니다.
{%- elsif ghes < 3.4 or ghae %} {% data reusables.enterprise-accounts.actions-runners-tab %}
1. **새로 추가** 드롭다운에서 **새 그룹** 을 선택합니다.
{%- endif %}
1. “그룹 이름”에 실행기 그룹의 이름을 입력합니다.
