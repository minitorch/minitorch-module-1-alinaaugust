[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16786855&assignment_repo_type=AssignmentRepo)
# MiniTorch Module 1

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1/module1/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py tests/test_module.py tests/test_operators.py project/run_manual.py

## Tests

(падает часть setup, починить ее полностью выше моих сил, но и там, и тут можно посмотреть пруфы, что все смысловые тесты проходят, и локально все тоже естественно хорошо)
![image](https://github.com/user-attachments/assets/6fc15ab6-15f0-40d4-bf13-05a946658189)


## Streamlit Part

### Simple Dataset

![image](https://github.com/user-attachments/assets/a2c3b70e-8a89-415e-b5c4-2ab7de6a43ce)
![image](https://github.com/user-attachments/assets/f94e3e9b-b524-4ea3-9440-a10d516e4680)

### Diag Dataset

(не хотелось тратить время на подбор параметров, поэтому жесткая сетка с 12 слоями и lr = 1)

![image](https://github.com/user-attachments/assets/23f7f2b8-28ce-424c-ab9e-8cfed6a9f5ab)
![image](https://github.com/user-attachments/assets/a4f0d0bf-6ea9-4593-8f8d-ea4f477b3987)

### Split Dataset

Тут вообще интересно получилось, 16 слоев, lr=0.5, выучилось как-то так. Другие варианты оказались еще хуже. Но как бы лосс на то и лосс, точность все равно высокая.
![image](https://github.com/user-attachments/assets/1ecbcbf1-6459-41c7-9212-0a15b88aafae)
![image](https://github.com/user-attachments/assets/8c101f72-7c19-4029-a4eb-c1625d0fef52)

### Xor Dataset

12 слоев, lr=0.5
![image](https://github.com/user-attachments/assets/00ca9fd6-6c09-4f91-946d-a5e7aa792fc3)
![image](https://github.com/user-attachments/assets/e8e6f111-2d69-45b7-8079-4cb66925820b)
![image](https://github.com/user-attachments/assets/0cca7378-8b06-444a-b003-8758e2a914c6)








