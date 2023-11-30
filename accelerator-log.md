# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=aci-adr&repo=go-app-gg",
  "projectName" : "go-app-gg"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .DS_Store matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .idea/aci-adr-go-base.iml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .idea/modules.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug aci-adr-go-base matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug go.mod matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug go.sum matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug main.go matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug service/.DS_Store matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug service/common/logger.go matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug service/dal/db.go matched [**] -> included
┃ ┃ ┃ ┗ ┗ Debug service/dal/mongodb_service.go matched [**] -> included
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
