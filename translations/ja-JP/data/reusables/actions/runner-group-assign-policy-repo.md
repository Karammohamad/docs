1. ランナーグループの名前を入力し、リポジトリアクセスのポリシーを割り当てます。

    You can configure a runner group to be accessible to a specific list of repositories, or to all repositories in the organization.{% ifversion ghec or ghes %} By default, only private repositories can access runners in a runner group, but you can override this. This setting can't be overridden if configuring an organization's runner group that was shared by an enterprise.{% endif %}
