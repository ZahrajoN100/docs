{%- ifversion ghec or ghes > 3.3 or ghae-issue-5091 %}
{% data reusables.enterprise-accounts.access-enterprise %}
{% data reusables.enterprise-accounts.policies-tab %}
{% data reusables.enterprise-accounts.actions-tab %}
{% data reusables.enterprise-accounts.actions-runners-tab %}
1. Haz clic en **Ejecutor nuevo**.
{% data reusables.actions.self-hosted-runner-configure %}
{%- elsif ghae or ghes < 3.4 %}
To add a self-hosted runner to an enterprise, you must be an enterprise owner.
{% data reusables.enterprise-accounts.access-enterprise %}
{% data reusables.enterprise-accounts.policies-tab %}
{% data reusables.enterprise-accounts.actions-tab %}
{% data reusables.enterprise-accounts.actions-runners-tab %}
1. Da clic en **Agregar nuevo** y luego en **Ejecutor nuevo**.
{% data reusables.actions.self-hosted-runner-configure %}
{%- endif %}
