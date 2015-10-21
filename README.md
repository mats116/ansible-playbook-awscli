# ansible-role-awscli
Ubuntu 14.04 LTS

## Synopsis

Install [awscli](https://aws.amazon.com/cli/).

Use [Bundled Installer](http://docs.aws.amazon.com/ja_jp/cli/latest/userguide/installing.html#install-bundle-other-os), instead of `pip`.

## Requirements

- Python 2 version 2.6.5+ or Python 3 version 3.3+

## Variables

| parameter | required | default | comments |
| --- | --- | --- | --- |
| awscli_install_dir | yes | /usr/local/aws |  |  |
| awscli_bin_location | yes | /usr/local/bin/aws |  |

## Examples

```yaml:paybook.yaml
- hosts: all
  sudo: yes
  roles:
    - role: awscli
      awscli_install_dir: /opt/aws
```
