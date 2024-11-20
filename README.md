from pptx import Presentation

# Создаем объект презентации
prs = Presentation()

# Слайд 1: Заголовок
slide = prs.slides.add_slide(prs.slide_layouts[0])
title = slide.shapes.title
subtitle = slide.placeholders[1]
title.text = "Теріске шығару: риторикадағы орны мен қолдану ерекшеліктері"
subtitle.text = "Курстық жұмыс\nРиторика пәні"

# Слайд 2: Мазмұны
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Мазмұны"
content.text = (
    "1. Кіріспе\n"
    "2. Негізгі бөлім\n"
    "   2.1 Риторикадағы теріске шығарудың мәні\n"
    "   2.2 Теріске шығарудың түрлері\n"
    "   2.3 Техникасы: стратегиялар мен әдістер\n"
    "   2.4 Қазақ риторикасындағы ерекшеліктер\n"
    "3. Қорытынды\n"
    "4. Пайдаланылған әдебиеттер"
)

# Слайд 3: Кіріспе
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Кіріспе"
content.text = (
    "• Тақырыптың өзектілігі:\n"
    "  Ақпараттық қоғамда дәлелді теріске шығару өзекті.\n"
    "• Мақсаты: теріске шығару әдістерін зерттеу.\n"
    "• Міндеттері:\n"
    "  - Риторикадағы орнын анықтау;\n"
    "  - Теріске шығару түрлерін жүйелеу;\n"
    "  - Қазақ шешендік өнерін талдау."
)

# Слайд 4: Риторикадағы теріске шығару
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Риторикадағы теріске шығару"
content.text = (
    "• Тарихи негіздері:\n"
    "  Ежелгі Греция (Сократ, Аристотель).\n"
    "• Байланысы:\n"
    "  Логика – аргументтердің дәлдігін тексеру;\n"
    "  Риторика – аудиторияға әсер ету."
)

# Слайд 5: Теріске шығарудың түрлері
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Теріске шығарудың түрлері"
content.text = (
    "• Логикалық: қарсы аргументтерді дәлелдеу.\n"
    "• Психологиялық: эмоцияларды пайдалану.\n"
    "• Этика-моралдық: әлеуметтік құндылықтарды қорғау."
)

# Слайд 6: Техникасы: стратегиялар мен әдістер
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Техникасы: стратегиялар мен әдістер"
content.text = (
    "• Аргументті жоққа шығару: фактілерді пайдалану.\n"
    "• Қарсы сұрақ қою: Сократтық әдіс.\n"
    "• Эмоцияларды басқару: юмор мен тыныштық сақтау."
)

# Слайд 7: Қазақ риторикасындағы теріске шығару
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Қазақ риторикасындағы теріске шығару"
content.text = (
    "• Айтыс өнері:\n"
    "  Ақындар қарсыластың пікірін шебер жоққа шығарады.\n"
    "• Шешендік өнер:\n"
    "  Қара сөз арқылы халық даналығын көрсету."
)

# Слайд 8: Қорытынды
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Қорытынды"
content.text = (
    "• Теріске шығару риторикада маңызды компонент.\n"
    "• Қазіргі саясатта, бизнес пен ғылымда кеңінен қолданылады."
)

# Слайд 9: Пайдаланылған әдебиеттер
slide = prs.slides.add_slide(prs.slide_layouts[1])
title = slide.shapes.title
content = slide.placeholders[1]
title.text = "Пайдаланылған әдебиеттер"
content.text = (
    "1. Аристотель. Риторика.\n"
    "2. Сократтың сұхбаттары.\n"
    "3. Жарықбаев Қ. Қазақ шешендік өнері.\n"
    "4. Оразбаева Ф. Қазіргі риторика негіздері.\n"
    "5. Әуезов М. Айтыс: дәстүр мен өнер."
)

# Сохранение презентации
prs.save("teriske_shygaru_presentation.pptx")
print("Презентация успешно создана и сохранена как 'teriske_shygaru_presentation.pptx'")
