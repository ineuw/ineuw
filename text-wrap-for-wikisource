# [ alt + m ]	text wrap bilingual
# 231009_0344 - alt-m-text-wrap.py

clipboard.fill_clipboard('')
time.sleep(0.1)

activetitle_ = window.get_active_title()
time.sleep(0.1)

selectall_ = '<ctrl>+a'
copy_ = '<ctrl>+<insert>'
paste_ = '<shift>+<insert>'
ctrlhome_ = '<ctrl>+<home>'
time.sleep(0.1)

keyboard.send_keys(selectall_)
time.sleep(0.1)

try:
    keyboard.send_keys(copy_)
    time.sleep(0.1)

    text_ = clipboard.get_clipboard()
    time.sleep(0.1)

except:
    time.sleep(0.1)

else:
    text_ = text_.strip()
    time.sleep(0.1)

    text_ = text_.replace('\n\n', '~~')
    time.sleep(0.1)

    text_ = text_.replace('-\n', '')
    time.sleep(0.1)

    text_ = text_.replace('\n', ' ')
    time.sleep(0.1)

    text_ = text_.replace('  ', ' ')
    time.sleep(0.1)

    text_ = text_.replace('~~', '\n\n')
    time.sleep(0.1)

clipboard.fill_clipboard(text_)
time.sleep(0.1)

keyboard.send_keys(paste_)
time.sleep(0.1)

keyboard.send_keys(ctrlhome_)
