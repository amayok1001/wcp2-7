# wcp2-7

## 条件分岐
### if
    ifの直後の記述した条件に当てはまっていればtrue
    - 比較演算子（<,<=,>,>=)
        == : 右辺と左辺が等しい
        != : 右辺と左辺が等しくない
    - 論理的比較演算子（二つ以上の条件で判定する場合）
        ! : 否定
        && : どちらの条件も正しければtrue
        || : どちらかの条件が正しければtrue

### elsif / else
    ifの条件に当てはまらなかった場合の処理を行う
    - else
    　どちらも当てはまらない, どれにも当てはまらない
    - elsif
    　ifかそれともelseifか（ふたつめの条件）