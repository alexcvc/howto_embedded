# AI Agent Conversational Vocabulary

A practical glossary of informal and semi-technical English words often used by AI coding agents, CLI assistants, software engineers, and technical documentation.

## Format

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|

---

## General Agent Workflow

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **tinkering** | **TIN-ker-ing** /ˈtɪŋ.kər.ɪŋ/ | experimenting with small changes | возиться, экспериментировать | Trying small code/config changes to understand behavior. |
| **deliberation** | **di-LIB-er-AY-shun** /dɪˌlɪb.əˈreɪ.ʃən/ | careful thinking before deciding | обдумывание, взвешенное обсуждение | Agent reasoning before choosing an implementation path. |
| **iteration** | **it-er-AY-shun** /ˌɪt.əˈreɪ.ʃən/ | repeated improvement cycle | итерация, повторный шаг улучшения | Improve code/docs step by step. |
| **iterate** | **IT-er-ayt** /ˈɪt.ə.reɪt/ | to repeat and improve | улучшать по шагам | “Let’s iterate on this design.” |
| **refine** | **ri-FINE** /rɪˈfaɪn/ | improve by making more precise | уточнить, доработать | Improve prompt, code, design, or documentation. |
| **polish** | **POL-ish** /ˈpɒl.ɪʃ/ | make clean and finished | отполировать, довести до аккуратного состояния | Final cleanup before commit/release. |
| **cleanup** | **KLEEN-up** /ˈkliːn.ʌp/ | removing unnecessary things | очистка, приведение в порядок | Remove dead code, old comments, unused files. |
| **follow-up** | **FOL-oh-up** /ˈfɒl.oʊ.ʌp/ | next action or continuation | последующее действие | Additional task after the main work. |
| **handoff** | **HAND-off** /ˈhænd.ɒf/ | passing work to someone/something else | передача задачи/контекста | Passing task context to another agent, developer, or system. |
| **checkpoint** | **CHECK-point** /ˈtʃek.pɔɪnt/ | saved progress point | контрольная точка | Point where implementation status is reviewed. |
| **baseline** | **BASE-line** /ˈbeɪs.laɪn/ | starting reference state | базовое состояние | Current stable behavior before changes. |
| **snapshot** | **SNAP-shot** /ˈsnæp.ʃɒt/ | saved state at a moment | снимок состояния | Project state, test result, or config at a point in time. |
| **drift** | **drift** /drɪft/ | slow deviation from original state | отклонение, расхождение | Docs drift from code; config drift from expected values. |
| **align** | **a-LINE** /əˈlaɪn/ | make consistent | согласовать, привести в соответствие | Align implementation with documentation or requirements. |
| **reconcile** | **REK-on-sile** /ˈrek.ən.saɪl/ | resolve differences | сверить и согласовать | Reconcile docs, tests, and code behavior. |
| **sync up** | **sink up** /sɪŋk ʌp/ | synchronize understanding/state | синхронизироваться | Sync code, docs, task status, or team understanding. |

---

## Planning and Analysis

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **breakdown** | **BRAYK-down** /ˈbreɪk.daʊn/ | structured decomposition | разбор, декомпозиция | Breaking a task into smaller steps. |
| **scope** | **skohp** /skoʊp/ | limits of work | рамки задачи, объём работ | What is included or excluded. |
| **out of scope** | **out of skohp** /aʊt əv skoʊp/ | not part of the task | вне рамок задачи | Work not included in the current plan. |
| **assumption** | **a-SUMP-shun** /əˈsʌmp.ʃən/ | something treated as true | предположение | Agent states assumptions before implementation. |
| **constraint** | **kon-STRAINT** /kənˈstreɪnt/ | limitation or rule | ограничение | Architecture, API, compatibility, or business rule. |
| **requirement** | **ri-KWIRE-ment** /rɪˈkwaɪr.mənt/ | required condition | требование | Functional or technical requirement. |
| **acceptance criteria** | **ak-SEP-tans cry-TEER-ee-a** /əkˈsep.təns kraɪˈtɪr.i.ə/ | conditions for accepting work | критерии приёмки | Used in tickets and GitHub issues. |
| **trade-off** | **TRAYD-off** /ˈtreɪd.ɒf/ | compromise between options | компромисс | Performance vs maintainability, speed vs safety. |
| **rationale** | **RASH-uh-NAL** /ˌræʃ.əˈnæl/ | reason behind a decision | обоснование | Why a design decision was made. |
| **intent** | **in-TENT** /ɪnˈtent/ | purpose | намерение, цель | Intent of code, design, or function. |
| **approach** | **a-PROACH** /əˈproʊtʃ/ | way of doing something | подход | Implementation approach. |
| **strategy** | **STRAT-uh-jee** /ˈstræt.ə.dʒi/ | high-level plan | стратегия | Overall technical direction. |
| **roadmap** | **ROHD-map** /ˈroʊd.mæp/ | planned sequence of future steps | дорожная карта | Future implementation plan. |
| **milestone** | **MILE-stohn** /ˈmaɪl.stoʊn/ | major progress point | этап, веха | Important delivery stage. |
| **backlog** | **BACK-log** /ˈbæk.lɒɡ/ | list of pending tasks | список невыполненных задач | GitHub issues, Jira tasks, TODOs. |

---

## Coding and Implementation

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **scaffolding** | **SKAF-fold-ing** /ˈskæf.əl.dɪŋ/ | initial structure | каркас, заготовка | Creating project/file/class structure. |
| **bootstrap** | **BOOT-strap** /ˈbuːt.stræp/ | initialize from scratch | начальная инициализация | Start project, DI, config, runtime setup. |
| **wire up** | **WIRE up** /waɪr ʌp/ | connect components | связать, подключить | Wire up services, DI, event handlers, UI. |
| **plumbing** | **PLUM-ing** /ˈplʌm.ɪŋ/ | internal connection code | техническая обвязка | Infrastructure code that connects parts. |
| **glue code** | **gloo kohd** /ɡluː koʊd/ | code connecting components | связующий код | Adapter or integration code. |
| **hook** | **hook** /hʊk/ | extension point or callback | хук, точка подключения | Git hook, Claude Code hook, event hook. |
| **entry point** | **EN-tree point** /ˈen.tri pɔɪnt/ | where execution starts | точка входа | Program.Main, CLI command handler. |
| **handler** | **HAND-ler** /ˈhænd.lər/ | code that handles an event/request | обработчик | Request handler, event handler. |
| **pipeline** | **PIPE-line** /ˈpaɪp.laɪn/ | sequence of processing steps | конвейер обработки | Import/export pipeline, validation pipeline. |
| **resolver** | **re-ZOL-ver** /rɪˈzɒl.vər/ | component that finds/derives result | резолвер, компонент разрешения | Resolve ID to object, `sAddr` to process signal. |
| **adapter** | **a-DAP-ter** /əˈdæp.tər/ | compatibility wrapper | адаптер | Converts one interface/model to another. |
| **wrapper** | **RAP-er** /ˈræp.ər/ | layer around something | обёртка | Wrapper over API/library/object. |
| **facade** | **fa-SAHD** /fəˈsɑːd/ | simplified interface | фасад | Simplifies access to complex subsystem. |
| **orchestrator** | **OR-kes-tray-ter** /ˈɔːr.kə.streɪ.tər/ | coordinator component | оркестратор, координатор | Coordinates several services/steps. |
| **dispatcher** | **dis-PATCH-er** /dɪˈspætʃ.ər/ | routes work/messages | диспетчер | Sends commands/events to handlers. |
| **factory** | **FAK-tuh-ree** /ˈfæk.tər.i/ | creates objects | фабрика | ModelFactory, ServiceFactory. |
| **builder** | **BIL-der** /ˈbɪl.dər/ | constructs complex object | билдер, построитель | ManifestBuilder, PackageBuilder. |
| **extractor** | **ik-STRAK-ter** /ɪkˈstræk.tər/ | extracts data | экстрактор | Extracts metadata, XML fields, model entries. |
| **validator** | **VAL-i-day-ter** /ˈvæl.ɪ.deɪ.tər/ | checks correctness | валидатор | JSON/XML/schema/business validation. |

---

## Testing and Verification

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **sanity check** | **SAN-i-tee check** /ˈsæn.ə.ti tʃek/ | quick basic correctness check | проверка на здравый смысл | Quick check before deeper testing. |
| **smoke test** | **smohk test** /smoʊk test/ | minimal test that system starts | минимальная проверка запуска | “Does it run at all?” |
| **happy path** | **HAP-ee path** /ˈhæp.i pæθ/ | normal successful scenario | успешный основной сценарий | Save package → open package → works. |
| **edge case** | **ej kays** /edʒ keɪs/ | unusual boundary scenario | граничный случай | Empty file, missing field, invalid package. |
| **corner case** | **KOR-ner kays** /ˈkɔːr.nər keɪs/ | rare edge scenario | редкий граничный случай | Rare but possible failure path. |
| **regression** | **ri-GRESH-un** /rɪˈɡreʃ.ən/ | something that used to work is broken | регрессия | New change breaks old behavior. |
| **roundtrip** | **ROUND-trip** /ˈraʊnd.trɪp/ | full cycle returning to equivalent state | полный цикл туда-обратно | Save → open → verify same data. |
| **test harness** | **test HAR-ness** /test ˈhɑːr.nəs/ | support structure for tests | тестовая обвязка | Code/tools for running test scenarios. |
| **fixture** | **FIX-chur** /ˈfɪks.tʃər/ | prepared test data/setup | тестовая фикстура | Sample XML/ZIP/config used in tests. |
| **mock** | **mok** /mɒk/ | simulated dependency | мок, имитация зависимости | Fake service used in tests. |
| **stub** | **stub** /stʌb/ | simple placeholder implementation | заглушка | Minimal fake implementation. |
| **fake** | **fayk** /feɪk/ | simplified test implementation | тестовая подмена | More functional than a stub. |
| **assertion** | **a-SER-shun** /əˈsɜːr.ʃən/ | test condition that must be true | утверждение в тесте | `Assert.Equal(...)`. |
| **coverage** | **KUV-er-ij** /ˈkʌv.ər.ɪdʒ/ | how much code is tested | покрытие тестами | Unit/integration test coverage. |
| **verification** | **ver-i-fi-KAY-shun** /ˌver.ɪ.fɪˈkeɪ.ʃən/ | confirmation that it works | проверка, верификация | Verify feature against requirements. |

---

## Debugging and Investigation

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **trace** | **trays** /treɪs/ | follow execution/data path | проследить | Trace request, file loading, function call. |
| **inspect** | **in-SPEKT** /ɪnˈspekt/ | examine carefully | проверить, изучить | Inspect logs, code, package content. |
| **investigate** | **in-VES-ti-gayt** /ɪnˈves.tɪ.ɡeɪt/ | research the cause | расследовать, исследовать | Investigate bug or inconsistent behavior. |
| **root cause** | **root kawz** /ruːt kɔːz/ | real underlying cause | первопричина | Root cause of failure. |
| **symptom** | **SIMP-tum** /ˈsɪmp.təm/ | visible problem | симптом | Error message is symptom, not root cause. |
| **reproduce** | **ree-pro-DOOS** /ˌriː.prəˈduːs/ | make the problem happen again | воспроизвести | Reproduce a bug locally. |
| **repro** | **REE-proh** /ˈriː.proʊ/ | reproduction case | воспроизведение бага | “Minimal repro” = minimal bug example. |
| **minimal repro** | **MIN-i-mal REE-proh** | smallest reproducible example | минимальный пример воспроизведения | Small test/project showing the bug. |
| **diagnostics** | **die-ag-NOS-tiks** /ˌdaɪ.əɡˈnɒs.tɪks/ | information for analysis | диагностика | Logs, traces, dumps, metrics. |
| **log output** | **log OUT-put** /lɒɡ ˈaʊt.pʊt/ | text produced by logs | вывод логов | Used to inspect runtime behavior. |
| **stack trace** | **stak trays** /stæk treɪs/ | call stack at error | стек вызовов | Exception stack trace. |
| **breakpoint** | **BRAYK-point** /ˈbreɪk.pɔɪnt/ | debugger stop point | точка останова | Used in Rider/Visual Studio debugging. |
| **watch** | **woch** /wɒtʃ/ | debugger expression monitor | наблюдение переменной | Watch variable value during debugging. |
| **step through** | **step throo** /step θruː/ | execute line by line | пройти пошагово | Step through code in debugger. |
| **hot path** | **hot path** /hɒt pæθ/ | frequently executed path | горячий путь выполнения | Performance-critical code path. |

---

## Errors and Reliability

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **fallback** | **FALL-back** /ˈfɔːl.bæk/ | backup option | запасной вариант | Use fallback if primary path fails. |
| **graceful failure** | **GRAYSS-ful FAYL-yur** /ˈɡreɪs.fəl ˈfeɪl.jər/ | controlled failure | корректная обработка отказа | Fail with clear error, not crash. |
| **fail fast** | **fayl fast** /feɪl fæst/ | stop early on invalid state | быстро падать при ошибке | Detect invalid input early. |
| **guardrail** | **GARD-rayl** /ˈɡɑːrd.reɪl/ | safety constraint | защитное ограничение | Prevent unsafe architecture/code changes. |
| **safety net** | **SAYF-tee net** /ˈseɪf.ti net/ | protection against mistakes | страховка | Tests or validation preventing regressions. |
| **robust** | **roh-BUST** /roʊˈbʌst/ | reliable under bad conditions | устойчивый, надёжный | Robust import/export handling. |
| **resilient** | **ri-ZIL-yent** /rɪˈzɪl.jənt/ | recovers from problems | отказоустойчивый | Resilient service or workflow. |
| **brittle** | **BRIT-l** /ˈbrɪt.əl/ | easily broken | хрупкий | Brittle tests or fragile parsing logic. |
| **flaky** | **FLAY-kee** /ˈfleɪ.ki/ | unreliable, sometimes failing | нестабильный | Flaky test passes and fails randomly. |
| **timeout** | **TIME-out** /ˈtaɪm.aʊt/ | operation took too long | тайм-аут | Request or test exceeded time limit. |
| **retry** | **ree-TRY** /ˌriːˈtraɪ/ | try again | повторная попытка | Retry failed network operation. |
| **deadlock** | **DED-lock** /ˈded.lɒk/ | processes wait forever | взаимная блокировка | Threads/tasks block each other. |
| **race condition** | **rays con-DISH-un** /reɪs kənˈdɪʃ.ən/ | timing-dependent bug | гонка данных | Bug caused by concurrent execution timing. |
| **leak** | **leek** /liːk/ | resource not released | утечка | Memory leak, handle leak, connection leak. |
| **corruption** | **kor-RUP-shun** /kəˈrʌp.ʃən/ | damaged data/state | повреждение данных | File/package/config corruption. |

---

## GitHub, PR, and Code Review

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **commit** | **kuh-MIT** /kəˈmɪt/ | saved Git change | коммит | Save changes to Git history. |
| **branch** | **branch** /bræntʃ/ | separate line of development | ветка | Feature branch, bugfix branch. |
| **merge** | **merj** /mɜːrdʒ/ | combine changes | слияние | Merge branch into main. |
| **pull request** | **pull ri-KWEST** /pʊl rɪˈkwest/ | request to merge changes | pull request, запрос на слияние | GitHub review workflow. |
| **review** | **ri-VYOO** /rɪˈvjuː/ | examine changes | ревью, проверка | Code review. |
| **diff** | **dif** /dɪf/ | difference between versions | различия | Git diff. |
| **patch** | **patch** /pætʃ/ | set of changes/fix | патч | Apply patch to code. |
| **changelog** | **CHANGE-log** /ˈtʃeɪndʒ.lɒɡ/ | list of changes | журнал изменений | Release notes or version changes. |
| **release notes** | **ri-LEES nohts** /rɪˈliːs noʊts/ | description of release changes | описание релиза | What changed in a release. |
| **merge conflict** | **merj KON-flikt** /mɜːrdʒ ˈkɒn.flɪkt/ | incompatible changes | конфликт слияния | Git cannot merge automatically. |
| **rebase** | **ree-BAYS** /ˌriːˈbeɪs/ | move branch on top of another | перебазирование | Rebase feature branch onto main. |
| **squash** | **skwosh** /skwɒʃ/ | combine commits | объединить коммиты | Squash multiple commits into one. |
| **cherry-pick** | **CHER-ee-pik** /ˈtʃer.i pɪk/ | apply one commit elsewhere | перенести отдельный коммит | Cherry-pick fix into release branch. |
| **rollback** | **ROLL-back** /ˈroʊl.bæk/ | revert to previous state | откат | Roll back bad change. |
| **revert** | **ri-VERT** /rɪˈvɜːrt/ | undo a change | отменить изменение | Git revert commit. |

---

## Documentation and Communication

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **write-up** | **WRITE-up** /ˈraɪt.ʌp/ | written explanation | описание, заметка | Technical explanation or summary. |
| **summary** | **SUM-uh-ree** /ˈsʌm.ər.i/ | short version | краткое резюме | Summary of work/results. |
| **recap** | **REE-kap** /ˈriː.kæp/ | short review of previous info | краткое повторение | Recap after investigation. |
| **notes** | **nohts** /noʊts/ | written remarks | заметки | Implementation notes. |
| **inline comment** | **IN-line KOM-ent** /ˈɪn.laɪn ˈkɒm.ent/ | comment inside code | строчный комментарий | Explains non-obvious code. |
| **docstring** | **DOK-string** /ˈdɒk.strɪŋ/ | documentation string in code | документирующая строка | Function/class documentation. |
| **README** | **READ-mee** /ˈriːd.miː/ | project introduction file | README-файл | Project usage and setup instructions. |
| **runbook** | **RUN-book** /ˈrʌn.bʊk/ | operational instruction document | эксплуатационная инструкция | How to operate/debug/deploy system. |
| **playbook** | **PLAY-book** /ˈpleɪ.bʊk/ | prepared procedure | сценарий действий | Procedure for repeated tasks. |
| **guideline** | **GUIDE-line** /ˈɡaɪd.laɪn/ | recommendation/rule | руководство, рекомендация | Coding or architecture guideline. |
| **convention** | **kon-VEN-shun** /kənˈven.ʃən/ | agreed style/rule | соглашение, конвенция | Naming convention, file convention. |
| **terminology** | **ter-mi-NOL-uh-jee** /ˌtɜːr.mɪˈnɒl.ə.dʒi/ | set of terms | терминология | Consistent naming in docs/code. |
| **wording** | **WER-ding** /ˈwɜːr.dɪŋ/ | exact phrasing | формулировка | Improve wording of GitHub issue. |
| **clarify** | **KLAR-i-fy** /ˈklær.ɪ.faɪ/ | make clear | уточнить, прояснить | Clarify requirements or behavior. |
| **ambiguous** | **am-BIG-yoo-us** /æmˈbɪɡ.ju.əs/ | unclear, multiple meanings | неоднозначный | Ambiguous requirement or command. |

---

## Architecture and Design

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **layering** | **LAY-er-ing** /ˈleɪ.ər.ɪŋ/ | separation into layers | слоистая архитектура | Core/Application/UI/Infrastructure layers. |
| **boundary** | **BOUND-uh-ree** /ˈbaʊn.dər.i/ | separation line | граница | Boundary between modules/layers. |
| **contract** | **KON-trakt** /ˈkɒn.trækt/ | agreed interface/rule | контракт | API contract, file format contract. |
| **interface** | **IN-ter-face** /ˈɪn.tər.feɪs/ | defined interaction surface | интерфейс | C# interface, API interface. |
| **abstraction** | **ab-STRAK-shun** /æbˈstræk.ʃən/ | simplified concept/interface | абстракция | Hide implementation details. |
| **decoupling** | **dee-KUP-ling** /ˌdiːˈkʌp.lɪŋ/ | reducing dependencies | развязка зависимостей | Keep UI separate from business logic. |
| **coupling** | **KUP-ling** /ˈkʌp.lɪŋ/ | dependency between parts | связанность | High coupling makes changes risky. |
| **cohesion** | **koh-HEE-zhun** /koʊˈhiː.ʒən/ | how well things belong together | связность внутри модуля | High cohesion is usually good. |
| **separation of concerns** | **sep-uh-RAY-shun of kon-SERNS** | separate responsibilities | разделение ответственностей | UI, domain, infrastructure separated. |
| **dependency injection** | **di-PEN-den-see in-JEK-shun** | providing dependencies externally | внедрение зависимостей | DI container, service registration. |
| **composition root** | **kom-puh-ZISH-un root** | central DI setup location | корень композиции | Where services are wired together. |
| **cross-cutting** | **kross-KUT-ing** | affects many parts | сквозной | Logging, localization, security, settings. |
| **single source of truth** | **SING-gul sors of trooth** | authoritative source | единый источник истины | One place owns correct data/state. |
| **source of truth** | **sors of trooth** | authoritative source | источник истины | Canonical data source. |
| **canonical** | **ka-NON-i-kal** /kəˈnɒn.ɪ.kəl/ | standard, normalized form | канонический | Canonical model, canonical JSON. |

---

## CLI and Agent Interaction

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **prompt** | **prompt** /prɒmpt/ | instruction to AI | запрос, инструкция | Task text sent to AI agent. |
| **context** | **KON-text** /ˈkɒn.tekst/ | information available to the agent | контекст | Files, previous messages, project state. |
| **tool use** | **tool yoos** /tuːl juːs/ | agent using external tool | использование инструмента | Read file, edit file, run command. |
| **shell command** | **shel kuh-MAND** | terminal command | команда shell | `dotnet test`, `git status`. |
| **flag** | **flag** /flæɡ/ | command-line option | флаг команды | `--help`, `--verbose`. |
| **option** | **OP-shun** /ˈɒp.ʃən/ | command parameter | параметр | CLI option. |
| **interactive mode** | **in-ter-AK-tiv mohd** | user-agent dialog mode | интерактивный режим | Agent waits for user input. |
| **non-interactive mode** | **non in-ter-AK-tiv mohd** | one-shot execution mode | неинтерактивный режим | Run command and exit. |
| **session** | **SESH-un** /ˈseʃ.ən/ | continuous work context | сессия | CLI agent session. |
| **resume** | **ri-ZOOM** /rɪˈzuːm/ | continue previous session | продолжить сессию | Resume previous agent work. |
| **compact** | **kom-PAKT** /kəmˈpækt/ | reduce/summarize context | сжать контекст | Compact long conversation context. |
| **permission** | **per-MISH-un** /pərˈmɪʃ.ən/ | allowed action | разрешение | Permission to edit files/run commands. |
| **approval** | **a-PROO-val** /əˈpruː.vəl/ | explicit confirmation | подтверждение | User approves risky action. |
| **sandbox** | **SAND-box** /ˈsænd.bɒks/ | isolated execution environment | песочница | Restricted environment for commands/code. |
| **dry run** | **dry run** /draɪ rʌn/ | simulate without applying changes | пробный запуск | Check what would happen without changing files. |

---

## Build, Packaging, and Release

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **build** | **bild** /bɪld/ | compile/package software | сборка | `dotnet build`. |
| **artifact** | **AR-ti-fakt** /ˈɑːr.tɪ.fækt/ | produced file/output | артефакт сборки | ZIP, EXE, DLL, package. |
| **bundle** | **BUN-dl** /ˈbʌn.dəl/ | group of files packaged together | пакет, набор файлов | Session Package, export bundle. |
| **package** | **PAK-ij** /ˈpæk.ɪdʒ/ | packaged output | пакет | NuGet package, ZIP package. |
| **manifest** | **MAN-i-fest** /ˈmæn.ɪ.fest/ | file describing package contents | манифест | `export.manifest.xml`. |
| **payload** | **PAY-load** /ˈpeɪ.loʊd/ | actual transported content | полезная нагрузка | Files inside ZIP or request. |
| **metadata** | **MET-a-day-ta** /ˈmet.əˌdeɪ.tə/ | data about data | метаданные | Version, hash, file name, timestamp. |
| **checksum** | **CHECK-sum** /ˈtʃek.sʌm/ | calculated integrity value | контрольная сумма | Used to detect file changes. |
| **hash** | **hash** /hæʃ/ | cryptographic/data fingerprint | хеш | SHA-256 hash of file/package. |
| **signature** | **SIG-na-chur** /ˈsɪɡ.nə.tʃər/ | proof of authenticity/integrity | подпись | XMLDSIG, digital signature. |
| **signing** | **SIGN-ing** /ˈsaɪn.ɪŋ/ | creating digital signature | подписание | Signing manifest/package. |
| **verification** | **ver-i-fi-KAY-shun** | checking validity | проверка | Verify signature/hash/package. |
| **deploy** | **di-PLOY** /dɪˈplɔɪ/ | install/release to environment | развернуть | Deploy app/service/tool. |
| **rollout** | **ROLL-out** /ˈroʊl.aʊt/ | gradual release | выкатывание | Rollout feature to users. |
| **release candidate** | **ri-LEES KAN-di-dayt** | almost-final release | кандидат в релиз | Pre-release version for testing. |

---

## Data, Files, and Models

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **schema** | **SKEE-ma** /ˈskiː.mə/ | structure definition | схема | JSON schema, XML schema. |
| **mapping** | **MAP-ing** /ˈmæp.ɪŋ/ | relation between things | сопоставление | `sAddr` to process signal mapping. |
| **lookup** | **LOOK-up** /ˈlʊk.ʌp/ | finding value by key | поиск по ключу | Lookup by UUID, ID, name. |
| **index** | **IN-deks** /ˈɪn.deks/ | structure for fast lookup | индекс | Database or in-memory index. |
| **cache** | **kash** /kæʃ/ | stored result for faster access | кэш | Cache loaded models or resolved data. |
| **deserialize** | **dee-SER-ee-uh-lize** | convert text/binary to object | десериализовать | JSON/XML to C# object. |
| **serialize** | **SER-ee-uh-lize** | convert object to text/binary | сериализовать | Object to JSON/XML/file. |
| **normalize** | **NOR-ma-lize** /ˈnɔːr.mə.laɪz/ | convert to standard form | нормализовать | Normalize file names, paths, model fields. |
| **canonicalize** | **ka-NON-i-ka-lize** | convert to canonical form | канонизировать | XML canonicalization for signing. |
| **hydrate** | **HY-drayt** /ˈhaɪ.dreɪt/ | fill object with data | наполнить объект данными | Load full model from stored data. |
| **flatten** | **FLAT-en** /ˈflæt.ən/ | convert hierarchy to flat list | расплющить структуру | XML tree to flat semantic entries. |
| **merge** | **merj** /mɜːrdʒ/ | combine data | объединить | Merge configuration sources. |
| **deduplicate** | **dee-DOO-pli-kayt** | remove duplicates | удалить дубликаты | Deduplicate entries/files/results. |
| **canonical model** | **ka-NON-i-kal MOD-el** | standard internal model | каноническая модель | Stable model used internally. |

---

## UI and User Flow

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **user flow** | **YOO-zer floh** | sequence of user actions | пользовательский сценарий | Save/open package flow. |
| **workflow** | **WORK-flow** /ˈwɜːrk.floʊ/ | work process | рабочий процесс | Agent workflow, user workflow. |
| **entry screen** | **EN-tree skreen** | first screen | начальный экран | MainForm or start page. |
| **dialog** | **DIE-uh-log** /ˈdaɪ.ə.lɒɡ/ | user interaction window | диалоговое окно | Save/Open confirmation dialog. |
| **prompt the user** | **prompt the YOO-zer** | ask user for input/confirmation | запросить пользователя | Ask before saving/opening. |
| **confirmation** | **kon-fer-MAY-shun** /ˌkɒn.fərˈmeɪ.ʃən/ | explicit approval | подтверждение | User confirms action. |
| **cancel path** | **KAN-sel path** | path when user cancels | сценарий отмены | What happens if user clicks Cancel. |
| **selection** | **se-LEK-shun** /sɪˈlek.ʃən/ | chosen item | выбор | Selected row/tree node/file. |
| **state** | **stayt** /steɪt/ | current condition/data | состояние | UI state, session state. |
| **dirty state** | **DIR-tee stayt** | unsaved-change state | состояние с несохранёнными изменениями | Document has unsaved changes. |
| **refresh** | **ri-FRESH** /rɪˈfreʃ/ | reload/update display | обновить | Refresh grid/tree/model. |
| **bind** | **bind** /baɪnd/ | connect data to UI | привязать данные | Bind ViewModel to Grid. |
| **binding** | **BIND-ing** /ˈbaɪn.dɪŋ/ | data connection | привязка данных | DevExpress/WinForms binding. |
| **view model** | **vyoo MOD-el** | UI-facing data model | модель представления | ViewModel for UI binding. |

---

## Informal Agent Expressions

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **nudge** | **nuj** /nʌdʒ/ | small push/correction | мягко подтолкнуть | Slightly adjust implementation or behavior. |
| **rough edges** | **ruff EJ-es** | unfinished/problematic details | шероховатости, недоработки | Small issues before final polish. |
| **tighten up** | **TY-ten up** | make stricter/cleaner | усилить, привести в порядок | Tighten validation or code structure. |
| **flesh out** | **flesh out** | add detail | раскрыть подробнее | Flesh out design, tests, documentation. |
| **clean slate** | **kleen slate** | fresh start | начать с чистого листа | Rebuild approach from scratch. |
| **quick win** | **kwik win** | easy useful improvement | быстрый полезный результат | Small change with high value. |
| **low-hanging fruit** | **loh-HANG-ing froot** | easy tasks first | простые задачи, лёгкая добыча | Easy fixes before complex work. |
| **rabbit hole** | **RAB-it hohl** | distracting deep investigation | кроличья нора, затягивающее исследование | Over-investigation outside the task. |
| **gotcha** | **GOT-cha** /ˈɡɒtʃ.ə/ | hidden trap/problem | подвох, ловушка | Non-obvious bug or limitation. |
| **quirk** | **kwerk** /kwɜːrk/ | strange behavior | странность, особенность | Library/API quirk. |
| **workaround** | **WORK-a-round** /ˈwɜːrk.ə.raʊnd/ | alternative solution | обходной путь | Temporary fix for limitation. |
| **band-aid fix** | **BAND-ayd fix** | temporary weak fix | временная заплатка | Quick fix, not proper solution. |
| **proper fix** | **PROP-er fix** | correct long-term fix | правильное исправление | Real architectural/code fix. |
| **future-proof** | **FYOO-chur proof** | resistant to future changes | устойчивый к будущим изменениям | Design that will survive future requirements. |
| **overkill** | **OH-ver-kill** /ˈoʊ.vər.kɪl/ | too much for the problem | чрезмерное решение | Too complex for current need. |

---

## Special Word: Moonwalking

| Word / Phrase | Pronunciation | English Meaning | Russian Meaning | Technical / Agent Context |
|---|---|---|---|---|
| **moonwalking** | **MOON-waw-king** /ˈmuːnˌwɔː.kɪŋ/ | moving backward while appearing to move forward | лунная походка; движение назад под видом прогресса | Sometimes used informally to describe fake progress, regression, or going backwards while seeming to advance. |

Example:

```text
The implementation is moonwalking: the code looks more complex, but the actual feature is not moving forward.
