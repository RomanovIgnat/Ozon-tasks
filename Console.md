1) grep 9 examples.txt

2) ps aux | grep 'python' (однако, отмечу, что это решение работает не слишком хорошо: поскольку например оно найдет себя или echo python, а какой-нибудь jython не найдет, можно было бы попытаться улучшить это, сделав, что-нибудь вроде cat /proc/[pid]/maps и дальше анализировать конкретные батчи памяти, чтобы выделить какие-нибудь характерные для питона последовательности)
