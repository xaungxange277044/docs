---
title: Eliminar una cuenta de una organización
intro: 'Cuando eliminas una organización, se eliminan también todos los repositorios, bifurcaciones de repositorios privados, wikis, propuestas, solicitudes de extracción y páginas del proyecto y de la organización. {% ifversion fpt or ghec %}Tu facturación terminará y, después de 90 días, el nombre de la organización estará disponible para que una cuenta de organización o de usuario nueva lo utilice.{% endif %}'
redirect_from:
  - /articles/deleting-an-organization-account
  - /github/setting-up-and-managing-organizations-and-teams/deleting-an-organization-account
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Delete organization
---

{% ifversion fpt or ghec %}
{% tip %}

**Sugerencia**: Si deseas cancelar tu suscripción paga, puedes [bajar la categoría de tu organización a {% data variables.product.prodname_free_team %}](/articles/downgrading-your-github-subscription) en lugar de eliminar la organización y su contenido.

{% endtip %}

{% endif %}

## 1. Haz una copia de respaldo del contenido de tu organización

{% ifversion not ghes %} After you delete an organization, {% data variables.product.company_short %} **cannot restore your content**. Therefore, before{% else %}Before{% endif %} you delete your organization, make sure you have a copy of all repositories, wikis, issues, and project boards from the account.

{% ifversion ghes %}
{% note %}

**Note:** If necessary, a site administrator for {% data variables.product.product_location %} may be able to partially restore a deleted organization. For more information, see "[Restoring a deleted organization](/admin/user-management/managing-organizations-in-your-enterprise/restoring-a-deleted-organization)."

{% endnote %}
{% endif %}

## 2. Elimina la organización

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
4. Junto a la parte inferior de la página de configuración de la organización, haz clic en **Eliminar esta organización**. ![Botón Eliminar esta organización](/assets/images/help/settings/settings-organization-delete.png)
