+++
title = "{{ replace .Name "-" " " | title }}"
description = "Baseline Alerts for {{ replace .Name "-" " " | title }} and associated resources and settings."
date = "{{ .Date | time.Format ":date_short" }}"
author = "CHANGE ME TO YOUR GITHUB USERNAME"
msAuthor = "CHANGE ME TO YOUR MICROSOFT ALIAS"
draft = false
+++

The baseline alerts in this guidance include {{ replace .Name "-" " " | title }} and associated resources and settings.

## Summary of Baseline Alert Policies

{{< table style="table-striped" >}}
| Policy                                    |
| :---------------------------------------------------------------------: 
| [PR-1 - CHANGE ME title](#pr-1---change-me-title) |
| [PR-2 - CHANGE ME title](#pr-2---change-me-title) |
{{< /table >}}

{{< alert style="info" >}}

{{< /alert >}}

## Policy Details

### PR-1 - CHANGE ME title

**Baseline Alert Policy**

FILL ME IN...

**Resources**

- [CHANGE ME LINK](https://aka.ms)
- [CHANGE ME LINK](https://aka.ms)

**Resource Graph Query/Scripts**

{{< collapse title="Show/Hide Query/Script" >}}

{{< code lang="sql" file="code/pr-1/pr-1.json" >}} {{< /code >}}

{{< /collapse >}}

<br><br>

### PR-2 - CHANGE ME title

**Baseline Alert Policy**

FILL ME IN...

**Resources**

- [CHANGE ME LINK](https://aka.ms)
- [CHANGE ME LINK](https://aka.ms)

**Resource Graph Query/Scripts**

{{< collapse title="Show/Hide Query/Script" >}}

{{< code lang="sql" file="code/pr-2/pr-21.json" >}} {{< /code >}}

{{< /collapse >}}

<br><br>
