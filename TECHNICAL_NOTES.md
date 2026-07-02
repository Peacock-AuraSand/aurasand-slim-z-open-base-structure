# TECHNICAL_NOTES / 技术参考说明

## 中文条款

### 资料定位

本文件用于说明 3DM 文件未完整表达、但有助于理解 AuraSand SLIM-Z 基础主体结构的图纸外结构信息。本文内容为结构理解与打样参考，不构成完整量产工艺包。

### 钢底板四角凸起

3DM 文件中未对钢底板四角凸起进行完整建模，仅在对应区域设置“四角凸起位置标记”。该标记用于提示制作者：实际结构中，钢底板四角存在后加工形成的微凸起特征。

当前建议参考凸起高度：约 0.1mm。

该高度为雀音匠当前结构中的参考参数，用于帮助理解基础主体结构与实际装配关系。不同钢板材料、厚度、硬度、表面处理、加工方式和装配条件，均可能影响最终推感、稳定性与耐用性。

### 实现方式边界

本项目不提供四角凸起的具体加工设备、治具方案、设备参数、加工路径、批量一致性控制方法或内部质检标准。制作者可根据自身加工条件自行验证实现方案。

### 材料、重量与配重建议

本开源图纸对应的官方产品主体材料为锆合金 702。若使用 3D 打印、钛合金或其他材料制作，成品重量、重心、手感、磁吸表现和滑动稳定性可能与官方量产商品存在差异。制作者应根据所选材料密度、加工方式和目标手感自行进行打样测试。对于 3D 打印方案，可能需要自行增加配重；对于钛合金等较轻材料方案，可根据实际重量需求考虑调整或填满减重孔。以上内容仅为材料与重量方向的参考建议，不构成官方量产工艺、加工标准或品质保证。

### 底板接触面纹路

3DM 文件中包含底板接触面同心圆纹路。该纹路用于表达接触面设计效果和结构参考，不代表官方量产加工方式。本项目不提供纹路实际加工方法、量产表面处理参数、具体加工刀路、供应链方案或质检标准。

### 螺丝与螺纹

本结构使用 M2 x 3 沉头螺丝。3DM 文件中的面盖底座未进行完整螺纹设计处理；实际制作时，制作者可要求供应商或加工方在对应位置加工为 M2 螺纹。具体底孔尺寸、有效咬合深度、加工方式和装配稳定性，仍需由制作者或加工方根据材料、加工条件和实际装配结果自行确认。

## English Terms

### Purpose of This File

This file explains structural information that is not fully modeled in the 3DM file but is useful for understanding the AuraSand SLIM-Z open base structure. These notes are provided for structural understanding and prototyping reference only. They are not a complete mass-production process package.

### Raised Points on the Four Corners of the Steel Bottom Plate

The 3DM file does not fully model the raised points on the four corners of the steel bottom plate. Instead, the corresponding areas use “four-corner raised-point position marks.” These marks indicate that the actual structure includes small raised features formed by post-processing at the four corners of the steel bottom plate.

Current recommended reference raised height: approximately 0.1 mm.

This height is a reference parameter currently used in Peacock's structure. It is provided to help users understand the relationship between the base structure and real assembly. Different steel materials, thicknesses, hardness, surface treatments, forming methods, and assembly conditions may affect final feel, stability, and durability.

### Implementation Boundary

This project does not provide the specific equipment, fixtures, machine parameters, processing path, batch-consistency control method, or internal quality-inspection standard used to create the raised corner features. Makers may verify their own implementation based on their own manufacturing conditions.

### Material, Weight, and Ballast Reference

The official product corresponding to this open drawing uses zirconium alloy 702 for the main body. If the drawing is used with 3D printing, titanium alloy, or other materials, the final weight, center of mass, feel, magnetic response, and sliding stability may differ from Peacock's official mass-production product. Makers should prototype and verify the result based on the selected material density, manufacturing method, and target feel. For 3D-printed versions, additional ballast may be required. For titanium alloy or other lighter-material versions, makers may consider adjusting or filling the weight-reduction holes according to the required final weight. These notes are material and weight references only. They are not official mass-production process instructions, manufacturing standards, or quality guarantees.

### Bottom-Plate Contact Pattern

The 3DM file includes a concentric contact pattern on the bottom plate. That pattern is provided to express the contact-surface design effect and structural reference. It does not represent Peacock's official mass-production processing method. This project does not provide the actual pattern-making method, production surface-treatment parameters, toolpath, supply-chain solution, or quality-inspection standard for that pattern.

### Screws and Threads

This structure uses M2 x 3 countersunk screws. The faceplate base in the 3DM file is not fully designed or modeled with threads. In actual production, makers may ask their supplier or manufacturer to machine M2 threads at the corresponding positions. Specific pilot-hole sizes, effective thread engagement, machining methods, and assembly stability must still be verified by the maker or manufacturer based on the selected material, machining conditions, and actual assembly results.
