---
rank: 5
related_endpoints:
  - get_users_id
  - get_users
related_guides:
  - applications/select
required_guides: []
related_resources:
  - user
alias_paths:
  - /docs/user-types
  - /docs/app-users
  - /docs/service-account
category_id: authentication
subcategory_id: authentication/user-types
is_index: true
id: authentication/user-types
type: guide
total_steps: 3
sibling_id: authentication
parent_id: authentication
next_page_id: ''
previous_page_id: authentication/user-types/managed-users
source_url: >-
  https://github.com/box/developer.box.com/blob/main/content/guides/authentication/user-types/index.md
fullyTranslated: true
---
# ユーザータイプ

There are a few types of users that an application might encounter. The key differences the Admin-level permissions of a user, and whether a user represents a real Box user or a virtual user that is only visible to platform applications.

The type of user affects the type of data an application has access to, as a user with Admin permissions will have different permissions than a regular user.

## 概要

<!-- markdownlint-disable line-length -->

以下に、Box APIで使用可能なユーザーのタイプの概要を示します。

|            | 管理者権限                        | 管理者以外の権限                 |
| ---------- | ---------------------------- | ------------------------ |
| 従来のユーザー    | [管理者ユーザー][admin]             | [管理対象ユーザー][managed-user] |
| プラットフォームのみ | [サービスアカウント][service-account] | [App User][app-user]     |

<!-- markdownlint-enable line-length -->

<Message>

# 自分のアプリケーションで使用するユーザーのタイプ

The type of user that an application is authenticated as is dependent on the type of application created, as well as the type of authentication used to create an Access Token.

</Message>

[admin]: https://support.box.com/hc/en-us/articles/360043694174-Understanding-Administrator-and-Co-Administrator-Permissions

[service-account]: guide://authentication/user-types/service-account/

[managed-user]: guide://authentication/user-types/managed-users

[app-user]: guide://authentication/user-types/app-users
