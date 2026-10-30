# Tags by Cluster

Кластеры: `PYTHON_ML`, `LOW_LEVEL`, `SECURITY`, `SQL_BI`, `SYSADMIN`, `BACKEND_OTHER`, `GAMEDEV`, `QA`, `HARDWARE`.
Термины дублируются между кластерами там, где это релевантно.

---

## PYTHON_ML

**Язык / рантайм:** `Python`, `Python 3.x`, `asyncio`, `asyncio.Semaphore`, `__slots__`,
`__int__`, `__index__`, `__format__`, `__add__`, `__mod__`, `__len__`, `__getitem__`, `__matmul__`,
`lru_cache`, `itertools.permutations`

**Библиотеки / фреймворки:** `numpy`, `scipy`, `pandas`, `matplotlib`, `scikit-learn`,
`TensorFlow`, `tf.keras`, `MobileNetV3Large`, `Pillow`, `OpenCV`, `requests`, `requests.Session`,
`Scrapy`, `Playwright`, `pymupdf`, `pymongo`, `aiohttp`

**Форматы данных и обработка:** `MongoDB`, `CSV`, `utf-8-sig`, `BOM`, `JSON`, `float("inf")`,
`pickle`, `TTL`, `os.replace`, `DICOM`, `BZIP2`, `LZMA`, `BWT`, `BMP`, `RLE8`, `RLE4`, `DIB`,
`BITMAPCOREHEADER`, `BITMAPINFOHEADER`, `BITFIELDS`, `ALPHABITFIELDS`, `PDF`, `xref`, `content stream`,
`CMap`, `Tj`, `TJ`, `EastAsianWidth`

**ML / DS / CV:** `ML`, `CelebA`, `face alignment`, `bounding box`, `5 landmarks`, `affine transform`,
`np.linalg.lstsq`, `clamp-to-edge`, `TSP`, `Held–Karp`, `dp[mask][last]`, `O(n²·2ⁿ)`,
`time.perf_counter`, `Buffon`

**Стеганография / RDH:** `LSB`, `LSB-steganography`, `get_k_layer`, `insert_k_layer`, `read_k_layer`,
`unpackbits`, `PSNR`, `SSIM`, `MSE`, `confidence intervals`, `inverse CDF`, `Acklam`,
`diff`, `central`, `scharr3`, `prewitt3`, `prewitt5`, `sobel3`, `sobel5`, `sobel7`, `roberts`,
`numpy convolution`, `valid`, `same`, `LANCZOS`, `Non-blind`, `Histogram Shifting`,
`zero-points`, `stable_argsort`, `HeapSort`, `QuickSort`, `BOSSbase`, `RDH`, `reversible data hiding`,
`linear hash function`, `StegoHash`, `BitStr`, `DiscrLog`, `Lambda`, `StegoContainer`, `GF(2)`,
`sampler2D`, `interpolation RDH`, `texels`

**Криптография (прикладная):** `BigInteger`, `Miller-Rabin`, `Lucas-Lehmer`, `Jacobi symbol`,
`BitSieve`, `probable_prime`, `modpow_mont`, `Montgomery`, `redc`, `extended Euclidean`,
`GMP`, `gmpy2`, `mpz`, `DH`, `MQV`, `safe prime`, `Sosemanuk`, `Serpent24`, `LFSR`, `FSM`, `bitslice`,
`S-boxes Osvik`, `DTV_digest`, `eSTREAM`, `PBKDF2-HMAC-SHA256`, `SHA-256`, `SeedSequence`, `PCG64`,
`AES`, `RC4`, `mul_by_02…0e`, `CBC`, `IGE`, `ECB`, `IOBase`, `BytesIO`, `E2EE`, `room_crypto`, `salt`, `verifier`,
`proof-of-knowledge`, `blob-store`, `fetch_blob`, `crypto.xor`

**Симуляция / алгоритмы:** `AnyLogic`, `discrete-event simulation`, `EventEngine`, `SortedList`,
`Poisson process`, `M/M/1`, `M/M/2`, `M/M/3`, `ρ = λ/μ`

**Профилирование / перф:** `profiling.py`, `measure()`, `PROFILING=1`, `atexit`,
`pack("<IIII")`, `b"".join`, `map(operator.xor)`, `crypto.xor`

**Скрейпинг / интеграции:** `2FA`, `captcha`, `page.on("response")`, `fnmatch`, `reverse engineering`,
`Wildberries CDN`, `Mail.ru internal API`, `hh.ru internal API`

---

## LOW_LEVEL

**Языки / системное:** `C`, `C++`, `OOP`, `Java`, `Cython`, `LLVM`, `Assembly`, `disassembler`,
`match-case`, `packed-switch`, `sparse-switch`

**Компиляторы / NPU-стек:** `TTIR`, `TTADAPTER`, `Triton-Ascend`, `AscendNPU-IR`, `HFusion`, `HIVM`,
`BiSheng compiler backend`, `intrinsics`, `CANN Toolkit`, `ACL`, `op-compiler`, `ccec`, `torch-npu`,
`triton-ascend`, `pytorch`, `FlagGems`, `Merge Request`

**Реверс / бинарные форматы:** `reverse engineering`, `ELF parser`, `disassembler`, `Intel x86/x64`,
`OSM PBF`, `.osm.pbf`, `protobuf`, `Google Protobuf`, `deserialization`, `safetensors`,
`source map`, `.js.map`, `VLQ`

**Деобфускация:** `AST`, `Babel`, `Node.js`, `deobfuscation`, `obfuscation`, `RC4`, `base64`,
`virtual machine`, `MRO`, `supers`

**Графика / GUI:** `OpenGL`, `Qt`, `VBO`, `IBO`, `OpenGL display lists`, `MathGL`, `Tkinter`, `Canvas`,
`DOM`, `JavaScript`, `TypeScript`, `requestAnimationFrame`, `api.addEventListener`,
`onAdded`, `onWidgetChanged`, `onRemoved`, `widgetValueStore`, `aiohttp`, `middleware`,
`keycode`, `keysym`

**Embedded:** `embedded systems`, `встроенные системы`, `Java-based Python executor`,
`самописный интерпретатор Python`, `компилятор Python`, `планиметрия`

**Производительность:** `Montgomery`, `redc`, `pack("<IIII")`, `map(operator.xor)`,
`профилирование`, `perf_counter`

---

## SECURITY

**Симметричная криптография:** `AES`, `RC4`, `Sosemanuk`, `Serpent24`, `LFSR`, `FSM`, `bitslice`,
`S-boxes Osvik`, `DTV_digest`, `TEST_VECTOR_128`, `eSTREAM`, `mul_by_02…0e`, `CBC`, `IGE`, `ECB`,
`IOBase`, `BytesIO`

**Асимметричная криптография:** `RSA`, `ElGamal`, `Эль-Гамаля`, `Shamir`, `Шамира`, `ГВ`,
`BigInteger`, `Miller-Rabin`, `Lucas-Lehmer`, `Jacobi symbol`, `BitSieve`, `probable_prime`,
`modpow_mont`, `Montgomery`, `redc`, `extended Euclidean`, `GMP`, `gmpy2`, `mpz`, `DH`, `MQV`,
`safe prime`, `gen_safe_prime`, `gen_subgroup_params`, `p = 2q+1`, `p = t·q+1`

**Стеганография / RDH:** `RDH`, `reversible data hiding`, `steganography`, `LSB-steganography`,
`Histogram Shifting`, `PSNR`, `SSIM`, `MSE`, `confidence intervals`, `BOSSbase`, `sampler2D`,
`interpolation RDH`, `texels`, `StegoHash`, `BitStr`, `DiscrLog`, `Lambda`, `StegoContainer`, `GF(2)`,
`XOR`, `polynomial division`, `Ryabko–Fionov`, `Paris2019`, `AMHM`, `He et al.`, `TIFS`,
`Dual Pairwise PEE`, `Daiyrbayeva et al.`

**E2EE / прикладное:** `E2EE`, `room_crypto`, `PBKDF2-HMAC-SHA256`, `SHA-256`, `salt`, `verifier`,
`proof-of-knowledge`, `data || sha256(data)`, `blob-store`, `uuid = os.urandom(16)`,
`fetch_blob`, `crypto.xor`

**Защита ПО / баг-фиксы:** `SQL injection`, `prepared statements`, `dualsha256`, `pbkdf2`,
`ORA-04091`, `PRAGMA AUTONOMOUS_TRANSACTION`, `mutating table`

---

## SQL_BI

**Oracle / PL/SQL:** `Oracle`, `PL/SQL`, `ER-диаграммы`, `ограничения целостности`,
`оконные функции`, `триггеры`, `SELECT`, `GROUP BY`, `HAVING`, `CONCAT`, `||`, `даты`,
`вложенные подзапросы`, `коррелированные подзапросы`, `JOIN`, `INNER JOIN`, `LEFT JOIN`, `self-join`,
`EMPLOYEES`, `DEPARTMENTS`, `LOCATIONS`, `COUNTRIES`, `DML`, `INSERT`, `UPDATE`,
`CREATE TABLE AS SELECT`, `CTAS`, `скалярные подзапросы`, `RANK`, `DENSE_RANK`, `ROW_NUMBER`,
`SUM() OVER`, `NTILE`, `LAG`, `LEAD`, `COVAR_SAMP`, `CORR`, `PARTITION BY`, `DDL`, `FOREIGN KEY`, `M:1`,
`CREATE SEQUENCE`, `BEFORE INSERT`, `mutating table`, `ORA-04091`,
`PRAGMA AUTONOMOUS_TRANSACTION`, `NEXTVAL`, `ROLLBACK`

**PostgreSQL:** `PostgreSQL 18.4`, `POSTGRES_USER_FILE`, `POSTGRES_PASSWORD_FILE`, `scram-sha-256`,
`pg_upgrade`, `\d+`, `\dT+`, `\df+`, `\sf+`, `SERIAL`, `DEFAULT nextval(...)`, `CHECK`,
`pg_roles`, `pg_authid`, `rolconfig`, `setdatabase = 0::oid`, `plpgsql`, `BEFORE INSERT OR UPDATE`,
`ANY`, `ALL`, `EXISTS`, `EXPLAIN ANALYZE`, `SubPlan`, `Hash Semi Join`, `InitPlan`, `shared hit`,
`mmap(MAP_SHARED)`, `WITH RECURSIVE`, `CORP.sql`, `crp_pid`, `LIMIT 1`, `quicksort`, `top-N heapsort`,
`CTE`, `Incremental Sort`, `Presorted Key`, `Run Condition`, `WindowAgg`, `convert_inserts.py`,
`wc2014.sql`, `multi-row`, `ljust`, `rjust`, `dynamic SQL`, `print_sal_v3`, `format('%L')`,
`format('%I')`, `concat_ws`, `array_append`, `RAISE`, `NOTICE`, `WARNING`, `EXCEPTION`,
`\set ON_ERROR_STOP on`, `psql`, `DROP PROCEDURE`, `pg_proc`

**MariaDB / репликация:** `MariaDB`, `Master-Master`, `CHANGE MASTER TO`, `SHOW SLAVE STATUS`,
`auto_increment_offset`

---

## SYSADMIN

**ОС / виртуализация:** `Linux`, `Windows`, `VirtualBox`, `VDI`, `MultiAttach`,
`дифференциальные диски`, `Host-Only`, `NAT`, `Internal network`, `static IP`, `DNS suffixes`,
`Windows Firewall`

**Сети / протоколы:** `TCP/IP`, `DNS`, `DHCP`, `NAT`, `VPN`, `HTTP/HTTPS`, `ICMP`,
`iptables`, `DNAT`, `SNAT`

**Сервисы:** `BIND9`, `Master/Slave`, `A/PTR`, `forwarders`, `Round-Robin`, `rrset-order`,
`OpenLDAP`, `slapd`, `nslcd`, `PAM`, `SSH`, `NTP`, `ntpd`, `iburst`, `stratum`, `jitter`

**Web / стек приложений:** `Nginx`, `PHP-FPM`, `PHP`, `sessions`, `prepared statements`

**Контейнеры / оркестрация:** `Docker`, `Dockerfile`, `envsubst`, `volumes`, `bridge`,
`docker-compose.yml`, `Docker Hub`, `Kubernetes`, `k8s`

**Администрирование СУБД:** `PostgreSQL 18.4`, `scram-sha-256`, `pg_upgrade`, `pg_roles`,
`pg_authid`, `rolconfig`, `psql`, `DROP PROCEDURE`, `pg_proc`

**Мониторинг / профилирование:** `profiling.py`, `measure()`, `PROFILING=1`, `atexit`, `aiohttp`,
`middleware`, `timeout`

---

## BACKEND_OTHER

**C# / .NET:** `C#`, `Avalonia`, `.NET`, `net8.0-windows`, `Windows API`, `MVVM`,
`Model → ModelView → View`, `ациклический граф зависимостей`, `C#-reflection`, `ER-диаграммы`,
`mutex`, `race condition`

**PHP / веб:** `PHP`, `PHP-FPM`, `Nginx`, `sessions`, `pbkdf2`, `dualsha256`, `prepared statements`,
`SQL injection prevention`

**Java / JVM:** `Java`, `packed-switch`, `sparse-switch`, `match-case`

**Git / процессы:** `GitHub`, `git`, `git-flow`, `main`, `develop`, `Merge Request`,
`корпоративная безопасность`, `IP-чистота`

**Инфраструктура как код:** `Docker`, `Dockerfile`, `docker-compose.yml`, `Docker Hub`,
`Kubernetes`

**API / интеграции:** `REST API`, `requests.Session`, `aiohttp`, `middleware`, `api.addEventListener`

**Прочее:** `LLVM`

---

## GAMEDEV

**3D / графика:** `OpenGL`, `OpenGL display lists`, `VBO`, `IBO`, `Qt`, `MathGL`, `Tkinter`, `Canvas`,
`3D-движок`, `perspective projection`, `view/proj-матрицы`, `Z-depth`, `SortedList`, `FPS-счётчик`,
`orbital rotation`, `FPS`, `планиметрия`

**Процедурная генерация:** `skin_generator`, `procedural vector image generator`,
`geometric primitives`, `кодогенерация растровых данных`, `кодогенерация векторных данных`

**ComfyUI / Stable Diffusion:** `ComfyUI`, `Stable Diffusion`, `CLIP`, `VRAM`, `safetensors`,
`Hugging Face`, `umt5_xxl`, `embeddings`, `attention mask`, `PreviewAny`, `AMD GPU Monitor`,
`MIT`, `Apache 2.0`

**Квантовые вычисления / визуализация:** `Bloch sphere`, `Qubit`, `from_Bloch`, `to_Bloch`,
`BooleanFunction`, `CompactMatrix`, `__matmul__`, `Deutsch–Jozsa`, `Hadamard`,
`кронекерово произведение`, `ancilla`, `|−⟩`, `|0⟩`, `AND`, `OR`

---

## QA

**Тестирование:** `test_primes.py`, `PrimeTest.java`, `100 001 known primes`,
`10 000 random non-primes`, `Mersenne primes до 2³²¹⁷ − 1`, `RLE8/RLE4 test round`

**Профилирование / бенчмарки:** `profiling.py`, `measure()`, `PROFILING=1`, `atexit`,
`time.perf_counter`, `T_brute / T_dp`, `stable_argsort`

**Верификация / приёмка:** `DTV_digest`, `TEST_VECTOR_128`, `eSTREAM`, `BOSSbase`, `medical`,
`portrait`, `PSNR ≥ 40 дБ`, `accepted == queue_length + finished`,
`ρ(sd1) = 0.94 vs ρ(sd2) = 1.32`, `buffers = (647, 0)`

---

## HARDWARE

**Embedded / низкий уровень:** `embedded systems`, `встроенные системы`,
`Java-based Python executor`, `Java-based Python interpreter`

**Медицинская визуализация:** `DICOM`

---

## Сквозные (встречаются в нескольких кластерах)

- `Docker` — `SYSADMIN`, `BACKEND_OTHER`
- `Kubernetes` / `k8s` — `SYSADMIN`, `BACKEND_OTHER`
- `PostgreSQL` — `SQL_BI`, `SYSADMIN`, `PYTHON_ML`
- `Linux` — `SYSADMIN`, `LOW_LEVEL`, `SECURITY`
- `Python` — `PYTHON_ML`, `LOW_LEVEL`, `QA`
- `C` / `C++` — `LOW_LEVEL`, `SECURITY`, `HARDWARE`
- `C#` — `BACKEND_OTHER`, `GAMEDEV`
- `git` / `git-flow` — `BACKEND_OTHER`, `LOW_LEVEL`
- `REST API` — `BACKEND_OTHER`, `PYTHON_ML`
- `profiling` / `perf_counter` — `PYTHON_ML`, `LOW_LEVEL`, `QA`
- `OpenGL` — `LOW_LEVEL`, `GAMEDEV`
- `Tkinter` — `LOW_LEVEL`, `GAMEDEV`, `PYTHON_ML`
- `AST` / `Babel` — `LOW_LEVEL`, `PYTHON_ML`
- `RC4` — `LOW_LEVEL`, `SECURITY`, `PYTHON_ML`
- `SHA-256` — `SECURITY`, `PYTHON_ML`, `LOW_LEVEL`
- `PSNR` / `SSIM` / `MSE` — `PYTHON_ML`, `SECURITY`, `QA`

---

## Пример вставки в описание вакансии

```text
О себе: пишу на Python, C++ и C#, разбираюсь в компиляторах, реверс-инжиниринге
и системном программировании; последние полтора года — LLM, RAG, стеганография и
прикладная криптография. Люблю доводить вещи до конца и копать вглубь, а не
останавливаться на «оно работает».

Портфолио проектов: https://github.com/VectorASD/index

tags: Python, C++, C#, SQL, PostgreSQL, Oracle, Docker, Kubernetes, Linux,
LLVM, OpenGL, Tkinter, PyTorch, TensorFlow, LangChain, RAG, E2EE,
стеганография, RDH, PSNR, SSIM, Rust, ...
```
Все теги через запятую — вставляются одной строкой после `tags:`, разделитель — `, `. Многоточие в примере — placeholder: на его месте должен быть полный список тегов соответствующего кластера.
