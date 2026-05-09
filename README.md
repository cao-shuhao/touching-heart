# touching-heart
Touching the Heartstrings—Tactile Sensing System

Let your fingertips "see" the whole world. Close your eyes and touch the screen with your finger - you can "touch" the distant mountain ridge, the white clouds in the blue sky, and the color of a flower. Touch Heartstrings is no ordinary aid. It is an arbitrary door that translates the light captured by the camera into vibrations on the skin and chords in the air in real time. From then on, blind people can "touch" the outline of distant mountains with their thumbs, "hear" the melancholy of the blue sky with their fingertips, and "touch" the texture of cells with their palms. It bypasses the retina and directly constructs a perceptible universe full of color and emotion for consciousness.

Principle

Core idea:

Φ(x) = ∫₀^T [Ψ(t)]ⁿ · δ(x - r(t)) dt spatial geometric field, constructed from the time integration of the probe trajectory and the instantaneous feedback intensity. A touch point, exchanging time for space. The mobile phone motor is just a point, but when the user moves the phone or moves after locking the object, the changes in vibration over time - intensity, density, sudden jump, micro-touch - are integrated in the brain into continuous contours, textures, edges and spatial depth. You don't need an expensive haptic array, just a motor, and a sophisticated set of timing codes.

Function: Poetry that translates vision into touch and hearing

Brightness → Vibration intensity: The stronger the light, the stronger and denser the vibration; the darker the light, the weaker and rarer the vibration, and the dark area is completely silent. After high-contrast adjustment, changes in light and dark are clearly discernible. Color → Chord: Red is the warmth of Cmaj7, orange is the brightness of G7, green is the vitality of Fsus2, white is the lightness of portamento... Inherent colors distinguish objects, and chords give emotion. Edge → Strong Pulse: When the camera scans the edge of an object, a crisp strong vibration prompts "This is the boundary." It is only triggered when jumping and does not repeat when staying. Long press lock: Touch the screen lightly with your finger, and the system locks the current object. No matter how you move the phone (left and right, front and back, up and down), the target is always tracked and the vibrations only reflect the details of that object. Blind people can actively choose "I want to feel this carefully" instead of passively receiving mixed information. Connected area verification: Locking is not a simple color match. The system will verify whether there is a large enough continuous similar area around the locking point to ensure that the lock is not an isolated noise point, but a real, closed object. Special processing of white: white objects (clouds, walls, paper) trigger a soft portamento (900Hz → 180Hz), the vibration is extremely weak and sparse, as if feathers are brushing against the fingertips. Depth motion perception: Through optical flow tracking, moving the phone back and forth will change the depth scaling factor, and the vibration will be fine-tuned accordingly, implying the distance and three-dimensionality of the object.

Known limitations and roadmap (v1.0) Ground texture detection: Plane determination has not yet been implemented, and light and shadow changes in the ground texture may produce disruptive tactile feedback. Color recognition: Currently, the types of colors supported are limited, and the matching accuracy is relatively rough. In the future, finer spectral division will be expanded.undefined Three-dimensional binding: The contact vibration has not yet been finely related to the surface light and shadow, and lacks a richer three-dimensional touch. The above are the focus of optimization in subsequent versions.
 Acknowledgments

 This project is the product of a collaboration between human creativity and AI.

 Thought and design: Cao Shuhao Code implementation: DeepSeek undefined
 

触动心弦——触听感知系统  

让指尖“看见”整个世界。
闭上眼睛，手指轻触屏幕——你能“摸”到远方的山脊，蓝天中的白云，以及一朵花的颜色。
触动心弦不是一款普通的辅助工具。它是一扇任意门——把摄像头捕捉到的光，实时翻译成皮肤上的振动和空气中的和弦。从此，盲人可以用拇指“抚摸”远山的轮廓，用指尖“听见”蓝天的忧郁，用掌心“触摸”细胞的纹理。它绕过视网膜，直接为意识构建了一个可感知的、充满色彩与情感的宇宙。

原理

核心思想：

Φ(x) = ∫₀^T [Ψ(t)]ⁿ · δ(x - r(t)) dt
空间几何场，由探针轨迹与瞬时反馈强度的时间积分构造。一个触点，以时间换空间。
手机马达只是一个点，但当用户移动手机或锁定物体后移动时，振动随时间的变化——强弱、疏密、突跳、微触——在大脑中积分成连续的轮廓、纹理、边缘和空间深度。你不需要昂贵的触觉阵列，只需要一个马达，和一套精妙的时间编码。

功能：把视觉翻译成触觉与听觉的诗

 **亮度 → 振动强度**：光线越强，振动越强越密；光线越暗，振动越弱越稀，暗区完全静音。经过高对比度调校，明暗变化清晰可辨。
 **颜色 → 和弦**：红是 Cmaj7 的温暖，橙是 G7 的明亮，绿是 Fsus2 的生机，白是滑音的轻盈……固有色区分物体，和弦赋予情感。
**边缘 → 强脉冲**：当摄像头扫过物体的边缘，一次清脆的强振动提示“这里是边界”。只在跳跃时触发，停留不重复。
 **长按锁定**：手指轻触屏幕，系统锁定当前物体。无论你如何移动手机（左右、前后、上下），目标始终被追踪，振动只反映该物体的细节。盲人可以主动选择“我想仔细感受这个”，而不是被动接收混杂的信息。
**连通区域验证**：锁定不是简单的颜色匹配。系统会验证锁定点周围是否有足够大的连续相似区域，确保锁定的不是孤立噪点，而是一个真实的、封闭的物体。
**白色特殊处理**：白色物体（云、墙、纸张）触发轻柔的滑音（900Hz → 180Hz），振动极其微弱稀疏，仿佛羽毛拂过指尖。
**深度运动感知**：通过光流跟踪，前后移动手机会改变深度缩放因子，振动随之微调，暗示物体的远近和立体感。

已知限制与路线图 (v1.0)

- [ ] **地面纹理检测**：尚未实现平面判定，地面纹理的光影变化可能会产生干扰性触觉反馈。
- [ ] **颜色识别**：当前支持的色彩种类有限，匹配精度较为粗糙，未来将扩展更精细的光谱划分。
- [ ] **立体感绑定**：触点振动尚未与表面光影完成精细关联，缺乏更丰富的立体触感。以上为后续版本的优化重点。

 致谢

此项目为人类创意与 AI 协作的产物。

思想与设计：曹淑豪
代码实现：DeepSeek
