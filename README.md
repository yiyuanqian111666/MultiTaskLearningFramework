MultiTaskLearningFramework/
│
├── README.md               # 项目说明，安装和使用教程
├── LICENSE                 # 开源许可证（MIT）
├── requirements.txt        # Python依赖（pybind11, numpy, scikit-learn等）
├── src/                    # C++核心代码
│   ├── mtl.h               # 头文件：定义多任务学习相关类
│   ├── mtl.cpp             # C++实现：多任务学习的核心功能
│   └── tasks.cpp           # C++实现：训练和任务管理
├── python/                 # Python接口代码
│   ├── mtl.py              # Python绑定C++代码，封装多任务学习模型
│   ├── test_mtl.py         # Python测试脚本，验证多任务学习模型
├── docs/                   # 项目文档
│   ├── tutorial.md         # 使用教程，如何扩展MTL功能
│   └── mtl_validation.md   # MTL验证方法说明
└── .gitignore              # Git忽略文件
