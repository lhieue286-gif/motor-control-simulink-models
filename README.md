# Motor Control Simulink Models

基于 MATLAB/Simulink 的电机控制仿真模型集合，包含 SPWM、SVPWM 和滑模观测器相关模型。

## 模型内容

| 目录 | 模型 | 说明 |
| --- | --- | --- |
| `SPWM/` | `untitled_final_waveforms.slx` | SPWM 仿真模型 |
| `SVPWM/` | `untitled_final_waveforms.slx` | SVPWM 仿真模型 |
| `滑模观测器/` | `untitled_final_waveforms_SOM_PLL_fixed.slx` | 带 PLL 的滑模观测器模型 |
| `滑模观测器/` | `yuan_untitled_final_waveforms_SOM_PLL_fixed.slx` | 滑模观测器模型的另一版本 |

## 环境要求

- MATLAB/Simulink R2023b 或兼容版本
- 模型所使用模块对应的 MATLAB 工具箱

## 使用方法

1. 克隆本仓库。
2. 在 MATLAB 中将仓库根目录设为当前工作目录。
3. 打开所需的 `.slx` 文件。
4. 检查模型参数和仿真时间后运行仿真。

例如：

```matlab
open_system(fullfile('SVPWM', 'untitled_final_waveforms.slx'));
```

## 仓库说明

`slprj/`、代码生成目录和其他 Simulink 临时文件已通过 `.gitignore` 排除，不属于模型源文件。

## 许可证

本项目采用 [MIT License](LICENSE)。
