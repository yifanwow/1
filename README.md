## Dark Wechat-WeChat Windows Client Dark Mode Project

### Project Introduction

The WeChat development team has shown a lazy and irresponsible attitude towards user needs, consistently refusing to develop a dark mode for the WeChat client on the Windows platform. This is highly inconvenient for users who frequently use WeChat at night. To address this issue, I decided to create an external program that implements a dark mode for the WeChat client on Windows.

### Implementation Method

Since it is not possible to directly modify the WeChat client's code, I plan to implement the dark mode using the following approach:

1. Capture the position and size of the WeChat window.
2. Create a transparent overlay window that is always on top of the WeChat window.
3. Periodically capture the content of the WeChat window.
4. Process the captured image to replace specific colors (such as white) with dark colors.
5. Draw the processed image onto the overlay window.

### Development Tasks

1. **Capture WeChat Window:**
   - Use Windows API to get the position and size of the WeChat window.

2. **Create Overlay Window:**
   - Design a transparent overlay window and ensure it is always on top of the WeChat window.

3. **Capture Window Content:**
   - Implement functionality to periodically capture the content of the WeChat window.

4. **Color Replacement:**
   - Develop image processing algorithms to replace specific colors with dark colors.

5. **Draw Processed Image:**
   - Draw the processed image onto the overlay window.

6. **Optimize Performance:**
   - Ensure the performance and stability of the program during operation.

7. **User Interface:**
   - Add a user interface to allow users to enable or disable dark mode.


## 微信Windows客户端暗黑模式项目

### 项目介绍

微信团队对于用户需求的模式慵懒和不负责任，一直拒绝在Windows平台上开发微信的暗黑模式。这对于经常在夜间使用微信的用户来说，非常不便。为了改善这一现状，我决定创建一个外部程序，为微信Windows客户端实现暗黑模式。

### 实现方法

由于无法直接修改微信客户端的代码，我计划通过以下方式实现暗黑模式：

1. 捕获微信窗口的位置和大小。
2. 创建一个透明的覆盖窗口，该窗口始终位于微信窗口之上。
3. 定期捕获微信窗口的内容。
4. 对捕获的图像进行处理，将特定颜色（如白色）替换为暗色。
5. 将处理后的图像绘制到覆盖窗口上。

### 待开发事项

1. **捕获微信窗口：**
   - 使用Windows API获取微信窗口的位置和大小。

2. **创建覆盖窗口：**
   - 设计一个透明的覆盖窗口，并确保其始终位于微信窗口之上。

3. **捕获窗口内容：**
   - 实现定期捕获微信窗口内容的功能。

4. **颜色替换：**
   - 开发图像处理算法，将特定颜色替换为暗色。

5. **绘制处理后的图像：**
   - 在覆盖窗口上绘制处理后的图像。

6. **优化性能：**
   - 确保程序运行时的性能和稳定性。

7. **用户界面：**
   - 添加用户界面，允许用户启用或禁用暗黑模式。
