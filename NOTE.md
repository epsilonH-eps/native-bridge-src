# 说明：源码快照

这个仓库是 `stellaris-mcp-native`（桥 DLL）的源码快照，用于在本机重新编译
`stellaris_bridge.dll`（cyberfish 版，供「群星链接器」注入）。

- 上游：stellaris-mcp-native（MIT，LICENSE 见本仓库）
- 编译：需要 Visual Studio 2022 Build Tools（C++）+ CMake 3.20+
- 依赖：MinHook v1.3.4、nlohmann/json v3.11.3（CMake FetchContent；离线时用
  `-DFETCHCONTENT_SOURCE_DIR_MINHOOK=...` / `-DFETCHCONTENT_SOURCE_DIR_NLOHMANN_JSON=...`）

本仓库只做快照，不代表上游项目本身。