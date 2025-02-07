<!-- start title -->

# GitHub Action: Run VS Code Server

<!-- end title -->
<!-- start description -->

Runs a web version of Visual Studio Code to debug GitHub Actions.

<!-- end description -->
<!-- start contents -->
<!-- end contents -->
<!-- start usage -->

```yaml
- uses: zongou/run-vscode-server@0.0.3
  name: Run VS Code server to debug
  if: ${{ failure() }}
  # with:
  #   # VS Code quality, optional, default value "stable", can be "stable" or "insider"
  #   quality: "stable"
  #   # VS Code settings, optional, default sets color theme to "Default Dark Modern"
  #   settings:
  #     default: |
  #       {
  #           "workbench.colorTheme": "Default Dark Modern"
  #       }
```

<!-- end usage -->
<!-- start inputs -->

| **Input**                 | **Description**  | **Default**                                                    | **Required** |
| ------------------------- | ---------------- | -------------------------------------------------------------- | ------------ |
| **<code>quality</code>**  | VS Code quality  | <code>stable</code>                                            | **false**    |
| **<code>settings</code>** | VS Code Settings | <code>{ "workbench.colorTheme": "Default Dark Modern" }</code> | **false**    |

<!-- end inputs -->
<!-- start outputs -->
<!-- end outputs -->
<!-- start [.github/ghadocs/examples/] -->
<!-- end [.github/ghadocs/examples/] -->
