### gendescription
# Цифровая платформа сопровождения скрининга / Digital screening support platform
### [О лаборатории "Цифровые технологии в общестенном здоровье" / About DPHT lab](dpht.itmo.ru)
# RU
## Актуальность
Программы скрининга являются важной составляющей для обеспечения и поддержания здорового образа жизни как отдельного человека, так и общества в целом, поскольку они позволяют выявить потенциальные проблемы здоровья на ранних стадиях и предотвратить их развитие.

Недостаток (или сложность) таких программ состоит в том, что чаще всего они проводятся вручную - оператор отвечает на телефонные звонки или сообщения, собирает данные о человеке, который заинтересовался скринингом, маршрутизирует его для проведения исследования и фиксирует результаты. В таком формате скрининг является ресурсоемким и времязатратным, но не всегда эффективным процессом. 

Предлагаемая **цифровая платформы сопровождения скрининга** представляет собой актуальное и научно-практическое решение, которое потенциально может оказать воздействие на многие аспекты современного общества и науки. Во-первых, такой проект предоставляет возможность улучшить процессы диагностики и прогнозирования различных заболеваний благодаря инновационным технологиям и потенциально применимым алгоритмам машинного обучения. Платформа цифрового скрининга является **универсальной и может быть использована практически для любых клинических задач** после уточнений и незначительных доработок. Кроме того, существующие исследования формируют новые методики и алгоритмы, способные увеличить точность скрининга и предсказания заболеваний, что открывает перспективы для развития медицины и улучшения здравоохранения.

Автоматизация скрининга играет немаловажную роль в процессе сборе качественных медицинских данных и формования эталонных наборов медицинских данных в соответсвии с Национальным проектом «Здравоохранение»  и это особенно важно, поскольку она позволяет снизить нагрузку на врачей, не выделяя сбор данных как отдельную задачу. 
## Общее описание проекта 
Цифровая платформа основана на микросервисной архитектуре, где каждый микросервис выполняет определенные функции, обеспечивая эффективное проведение процесса скрининга и анализа медицинских данных. Ниже перечислены функциональные компоненты платформы:
1.  **Заполнение анкеты пациентом**: первый микросервис предоставляет возможность пациенту заполнить анкету, содержащую информацию о его медицинской истории, факторах риска и симптомах. На основе этих данных платформа решает, подходит ли пациент для проведения скрининга.
2.  **Приглашение на скрининг** через оператора: оператор при положительном решении связывается с участником скрининга и приглашает его на прием и осуществляет дальнейшую координацию, а также видит календарь того, когда необходимо пригласить участников на повторный прием или первичный в случае несоответствия параметрам отбора. 
3.  **Получение мультимодальных медицинских изображений** из PACS медицинской организации: этот микросервис позволяет получать медицинские изображения из Picture Archiving and Communication System (PACS) медицинской организации. Эти изображения могут включать рентгенограммы, КТ, МРТ и другие виды обследования.
4.  **Обезличивание** медицинских данных в соответсвии с требованиями по защите информации. 
5.  **Разметка данных** **_вручную_** или с использованием _**алгоритмов искусственного интеллекта**_.
6.  Отправка размеченных данных для **формирования набора данных**: размеченные данные используются для формирования набора данных, который может использоваться для анализа и диагностики.
7. Отправка в медицинскую организацию с **формированием протокола** по установленной форме: платформа генерирует протокол о результатах скрининга, который отправляется в медицинскую организацию. Такой протокол содержит информацию о выявленных аномалиях, результатах анализа и рекомендациях для пациента и соответствует форме медицинской организации.
8.  Возможность **графической интерпретации** результатов: для удобства врачей и медицинского персонала платформа предоставляет возможность графической интерпретации результатов скрининга, что упрощает визуальное восприятие данных и формирование необходимых отчетов для выгрузки и предоставления по запросу.
	
Такой модульный подход к разработке платформы обеспечивает высокую гибкость и эффективность в проведении скрининга и обработке медицинских данных, что помогает улучшить качество и точность диагностики в медицинской области. Архитектура платформы представлена на схеме ниже.

![Архитектура предлагаемой платформы](https://github.com/DPHT-laboratory-ITMO/gendescription/blob/6f9885270b519f5b6b76e42bd70e0ee1c0674141/Scheme%20of%20DSSP.png)

 
## Полученные результаты
Здесь предсталвены результаты команды, полученные в течение работы над проектом, в том числе выступления на конференциях, публикации и прочее.
- Публикации:
	- [Препринт](http://arxiv.org/abs/2310.08532)
- Конференции:
- Конкурсы:
# EN
## Relevance
Screening programs are an important component for ensuring and maintaining a healthy lifestyle for both an individual and society as a whole, since they allow identifying potential health problems at an early stage and preventing their development.

Disadvantage (or complexity) such programs consist in the fact that they are most often carried out manually - the operator answers phone calls or messages, collects data about a person who is interested in screening, routes it for research and records the results. In this format, screening is a resource-intensive and time-consuming, but not always an effective process. 

The proposed **digital screening support platform** represents an actual and scientific and practical solution that can potentially have an impact on many aspects of modern society and science. Firstly, such a project provides an opportunity to improve the processes of diagnosis and prediction of various diseases thanks to innovative technologies and potentially applicable machine learning algorithms. The digital screening platform is **universal and can be used for almost any clinical tasks** after refinements and minor improvements. In addition, existing research forms new techniques and algorithms that can increase the accuracy of screening and disease prediction, which opens up prospects for the development of medicine and improvement of healthcare.

Automation of screening plays an important role in the process of collecting high-quality medical data and forming reference sets of medical data in accordance with the National Project "Healthcare" and this is especially important because it reduces the burden on doctors without singling out data collection as a separate task.
## General description
The digital platform is based on a microservice architecture, where each microservice performs certain functions, ensuring effective screening and analysis of medical data. The functional components of the platform are listed below:
1. **Filling out the questionnaire by the patient**: the first microservice provides an opportunity for the patient to fill out a questionnaire containing information about his medical history, risk factors and symptoms. Based on this data, the platform decides whether the patient is suitable for screening.
2. **Invitation to screening **through an operator: if the decision is positive, the operator contacts the screening participant and invites him to an appointment and carries out further coordination, and also sees a calendar of when it is necessary to invite participants to a repeat appointment or primary in case of non-compliance with the selection parameters.
3. **Receiving multimodal medical images** from the PACS of a medical organization: This microservice allows you to receive medical images from the Picture Archiving and Communication System (PACS) of a medical organization. These images may include X-rays, CT scans, MRI scans, and other types of examinations.
4. **Depersonalization of medical data** in accordance with information protection requirements.
5. **Marking up data** manually or using artificial intelligence algorithms.
6. Sending marked-up data to **form a data set**: Marked-up data is used to form a data set that can be used for analysis and diagnostics.
7. Sending **a protocol in the prescribed** formto a medical organization : the platform generates a protocol on the results of screening, which is sent to the medical organization. Such a protocol contains information about the detected anomalies, the results of the analysis and recommendations for the patient and corresponds to the form of the medical organization.
8. Possibility of **graphical interpretation** of results: for the convenience of doctors and medical personnel, the platform provides the possibility of graphical interpretation of screening results, which simplifies the visual perception of data and the formation of necessary reports for uploading and providing on request.

This modular approach to the development of the platform provides high flexibility and efficiency in screening and processing medical data, which helps to improve the quality and accuracy of diagnostics in the medical field.

## Related results 
Here are the team's results obtained during the work on the project, including presentations at conferences, publications, and so on.
- Publications:
	- [Preprint](http://arxiv.org/abs/2310.08532 )
- Conferences:
- Contests:
