# gitstats PYTHON3版本

## 说明

* 在PYTHON 3.11上测试通过

## 用法

```bash
# 统计代码一个git项目的代码信息并输出到一个目录中
./gitstats <git_repo_dir> <output_dir>

# 只打印项目总行数，其余不输出任何东西
./gitstats --only-total-lines <git_repo_dir> <output_dir>
```