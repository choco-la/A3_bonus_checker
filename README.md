# A3! Bonus Checker
A3!のチーム編成ごとのボーナスポイントを計算します


`$ ./a3_bonus_checker.py | grep "'ac': 60"`

    ('幸', 'シトロン', '丞', '綴', '臣'): {'sr': 10, 'co': 20, 'ac': 60}

`$ ./a3_bonus_checker.py  -m "至" "真澄" "臣" "太一" "一成" --guest`

    ('十座', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 10}
    ('万里', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 20}
    ('三角', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 10}
    ('天馬', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 20}
    ('誉', '臣', '真澄', '太一', '一成', '至'): {'co': 30, 'sr': 0, 'ac': 10}
    ('椋', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 10}
    ('左京', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 10, 'ac': 10}
    ('シトロン', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 10}
    ('綴', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 10, 'ac': 10}
    ('東', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 20}
    ('密', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 10, 'ac': 10}
    ('咲也', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 0, 'ac': 10}
    ('紬', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 10, 'ac': 10}
    ('丞', '臣', '真澄', '太一', '一成', '至'): {'co': 10, 'sr': 10, 'ac': 10}
    ('幸', '臣', '真澄', '太一', '一成', '至'): {'co': 20, 'sr': 0, 'ac': 20}
