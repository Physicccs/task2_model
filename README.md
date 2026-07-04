# task2_model

支持两种模型文件：

1. .py 文件（推荐，任何算法都行）：文件里包含 RobotPolicy 类，实现
class RobotPolicy:
    def act(self, t, active, pos=None):
        # t: 当前秒；active: [(出现时刻, x, y, v), ...] 坐标1..10
        # pos: 机器人当前位置 (x, y)
        return (dx, dy)   # (0,0)/(±1,0)/(0,±1)
1. 每秒调用一次——就是我们封装版 robot_policy.py 的接口，直接把那个文件当模板发给同学即可。
