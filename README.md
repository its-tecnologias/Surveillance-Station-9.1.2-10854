## [Liceças para Surveillance Station 9.1.2-10854]
---
### Agendador de Tarefas
- Painel de Controle -> Agendador de Tarefas
- Criar -> Tarefa Agendada -> Script definido pelo usuário
- Geral: Usuário = root, desmarque Ativar
- Configurações da Tarefa: Script definido pelo usuário = ...
- OK - OK
- Clique e execute a tarefa.
- Exclua esta tarefa quando ver que há 58 licenças.

![image](https://github.com/user-attachments/assets/bf24f8d2-1386-4d46-8a98-dfb02ef64060)

### A. x86_64 (9.1.2-10854)
- Link de download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.2-10854/SurveillanceStation-x86_64-9.1.2-10854.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-x86_64/install_license)
```

### B. x86_64_openvino (9.1.1-10728)
- Link de download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.1-10728/SurveillanceStation-x86_64-9.1.1-10728_openvino.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-x86_64_openvino/install_license)
```

### C. armada38x (9.0.2-10061)
- Link de download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.0.2-10061/SurveillanceStation-armada38x-9.0.2-10061.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-armada38x/install_license)
```

---
### Remover Licença
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/license/remove_license)
```
