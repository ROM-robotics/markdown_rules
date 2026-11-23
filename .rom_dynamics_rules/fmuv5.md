# $\color{#00c853}{\text{CUAV V5 nano FMUv5}}$

Repo: `cuav_v5_nano_fmuv5`

## $\color{red}{\text{Markdown ဖိုင်စာရင်း}}$

Repo root ကနေ relative path နဲ့ ဖော်ပြထားပါတယ်။ ဖိုင်အသစ်ထည့်ရင် ဒီစာရင်းကို update လုပ်ပါ ([./AGENTS.md](./AGENTS.md) ကိုကြည့်ပါ)။

### $\color{cyan}{\text{Repo ဆိုင်ရာ}}$

- [./AGENTS.md](./AGENTS.md) : Copilot/agent အတွက် ညွှန်ကြားချက် (source of truth၊ markdown စည်းမျဉ်း)

## $\color{red}{\text{01 ArduPilot}}$

- [./01_ardu_pilot/README.md](./01_ardu_pilot/README.md) : ArduPilot မှတ်စုများအတွက် directory index

### $\color{cyan}{\text{00 README folder (ArduPilot)}}$

- [./01_ardu_pilot/00_README/00_prompt.md](./01_ardu_pilot/00_README/00_prompt.md) : စတင်လေ့လာရန် prompt (CUAV V5 nano quick start နှင့် ArduPilot overview)
- [./01_ardu_pilot/00_README/01_ardupilot_firmware_architecture_analysis_guide.md](./01_ardu_pilot/00_README/01_ardupilot_firmware_architecture_analysis_guide.md) : ArduPilot firmware code analysis လမ်းညွှန် (CUAVv5Nano / ChibiOS အပိုင်း ၇ ပိုင်း)
- [./01_ardu_pilot/00_README/02_basic_qa.md](./01_ardu_pilot/00_README/02_basic_qa.md) : အခြေခံ Q and A (PM2၊ board target ရွေးချယ်ပုံ၊ waf build command)
- [./01_ardu_pilot/00_README/03_FirmwareSetup.md](./01_ardu_pilot/00_README/03_FirmwareSetup.md) : ArduPilot firmware build၊ Flash အသုံးပြုမှု၊ hwdef.dat configuration၊ PX4 `default.px4board` နှင့် နှိုင်းယှဉ်ချက်၊ V5 nano ပေါ် flash လုပ်ခြင်း
- [./01_ardu_pilot/00_README/04_signal_probing_after_flash_rom-Copter-4.5.7_branch.md](./01_ardu_pilot/00_README/04_signal_probing_after_flash_rom-Copter-4.5.7_branch.md) : Copter-4.5.7 flash ပြီးနောက် peripheral မတပ်ဘဲ IO probe လုပ်နိုင်မှု၊ bench စမ်းသပ်နည်းနှင့် ကန့်သတ်ချက်များ
- [./01_ardu_pilot/00_README/05_how_to_custom_hitl.md](./01_ardu_pilot/00_README/05_how_to_custom_hitl.md) : ArduCopter SITL နှင့် Gazebo Harmonic ချိတ်ဆက်ခြင်း၊ V5 nano custom HITL လိုအပ်ချက်များနှင့် လုပ်ဆောင်မှုအစဉ်
- [./01_ardu_pilot/00_README/06_sitl.md](./01_ardu_pilot/00_README/06_sitl.md) : Gazebo Harmonic SITL ဖြင့် ArduCopter နှစ်စီး run ပြီး runner/follower သတ်မှတ်ပုံ

### $\color{cyan}{\text{Research prompts (ArduPilot)}}$

- [./01_ardu_pilot/01_startup_sequence_research/00_prompt.md](./01_ardu_pilot/01_startup_sequence_research/00_prompt.md) : Startup sequence (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/02_hal_and_drivers_research/00_prompt.md](./01_ardu_pilot/02_hal_and_drivers_research/00_prompt.md) : HAL နှင့် drivers (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/03_os_ipc_scheduler_middleware_research/00_prompt.md](./01_ardu_pilot/03_os_ipc_scheduler_middleware_research/00_prompt.md) : ChibiOS, AP Scheduler, Singleton Access (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/04_state_estimation_research/00_prompt.md](./01_ardu_pilot/04_state_estimation_research/00_prompt.md) : State estimation / EKF3 (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/05_fc_loops_and_controller_allocation_research/00_prompt.md](./01_ardu_pilot/05_fc_loops_and_controller_allocation_research/00_prompt.md) : Attitude/Position control loops နှင့် AP Motors mixing (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/06_flight_modes_mavlink_research/00_prompt.md](./01_ardu_pilot/06_flight_modes_mavlink_research/00_prompt.md) : Flight modes နှင့် GCS MAVLink (လက်ရှိ အလွတ်)
- [./01_ardu_pilot/07_heap_memory_management/00_prompt.md](./01_ardu_pilot/07_heap_memory_management/00_prompt.md) : ChibiOS Heap နှင့် Memory management prompt (လက်ရှိ အလွတ်)

## $\color{red}{\text{02 PX4 Autopilot}}$

- [./02_px4_autopilot/README.md](./02_px4_autopilot/README.md) : PX4 Autopilot မှတ်စုများအတွက် directory index

### $\color{cyan}{\text{00 README folder}}$

- [./02_px4_autopilot/00_README/00_prompt.md](./02_px4_autopilot/00_README/00_prompt.md) : စတင်လေ့လာရန် prompt (CUAV V5 nano quick start)
- [./02_px4_autopilot/00_README/01_px4_firmware_architecture_analysis_guide.md](./02_px4_autopilot/00_README/01_px4_firmware_architecture_analysis_guide.md) : PX4 firmware code analysis လမ်းညွှန် (အပိုင်း ၇ ပိုင်း)
- [./02_px4_autopilot/00_README/02_basic_qa.md](./02_px4_autopilot/00_README/02_basic_qa.md) : အခြေခံ Q and A (PM2၊ release ရွေးချယ်ပုံ၊ build command)
- [./02_px4_autopilot/00_README/03_FirmwareSetup.md](./02_px4_autopilot/00_README/03_FirmwareSetup.md) : PX4 firmware build၊ Flash configuration၊ boardconfig ရွေးချယ်မှုနှင့် V5 nano ပေါ် flash လုပ်ခြင်း

### $\color{cyan}{\text{Research prompts}}$

- [./02_px4_autopilot/01_startup_sequence_research/00_prompt.md](./02_px4_autopilot/01_startup_sequence_research/00_prompt.md) : Startup sequence (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/02_hal_and_drivers_research/00_prompt.md](./02_px4_autopilot/02_hal_and_drivers_research/00_prompt.md) : HAL နှင့် drivers (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/03_os_ipc_uorb_middleware_research/00_prompt.md](./02_px4_autopilot/03_os_ipc_uorb_middleware_research/00_prompt.md) : OS, IPC, uORB (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/04_state_estimation_research/00_prompt.md](./02_px4_autopilot/04_state_estimation_research/00_prompt.md) : State estimation (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/05_fc_loops_and_controller_allocation_research/00_prompt.md](./02_px4_autopilot/05_fc_loops_and_controller_allocation_research/00_prompt.md) : Flight control loops (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/06_commander_mavlink_research/00_prompt.md](./02_px4_autopilot/06_commander_mavlink_research/00_prompt.md) : Commander နှင့် MAVLink (လက်ရှိ အလွတ်)

### $\color{cyan}{\text{07 heap memory management folder}}$

- [./02_px4_autopilot/07_heap_memory_management/00_prompt.md](./02_px4_autopilot/07_heap_memory_management/00_prompt.md) : Heap memory prompt (လက်ရှိ အလွတ်)
- [./02_px4_autopilot/07_heap_memory_management/01_basic_qa.md](./02_px4_autopilot/07_heap_memory_management/01_basic_qa.md) : NuttX/RTOS၊ heap၊ DMA/DTCM နဲ့ mutex/semaphore/atomic/future အခြေခံ Q and A
- [./02_px4_autopilot/07_heap_memory_management/02_memory_management.md](./02_px4_autopilot/07_heap_memory_management/02_memory_management.md) : fmu-v5 memory map နှင့် memory management (Mermaid diagram)

### $\color{cyan}{\text{08 firmware design folder}}$

- [./02_px4_autopilot/08_firmware_design/01_basic_firmware_design.md](./02_px4_autopilot/08_firmware_design/01_basic_firmware_design.md) : fmu-v5 (PX4 v1.17) firmware design (layered architecture၊ boot sequence၊ rcS၊ sensors၊ uORB flow၊ work queues၊ module အုပ်စုများ၊ Mermaid diagram ၇ ခု)

### $\color{cyan}{\text{99 PSA Q and A folder}}$

- [./02_px4_autopilot/99_psa_qa/01_position.md](./02_px4_autopilot/99_psa_qa/01_position.md) : GPS နှင့် local/global position ရယူပုံ (uORB၊ C++ subscription၊ console၊ NED coordinate နှင့် MAVLink)
- [./02_px4_autopilot/99_psa_qa/02_all_logs.md](./02_px4_autopilot/99_psa_qa/02_all_logs.md) : ROS မပါဘဲ SD/SITL ULog၊ QGC telemetry/application logs၊ console/crash logs ရယူပုံနှင့် logging configuration
- [./02_px4_autopilot/99_psa_qa/03_px4_cuav_v5_nano_to_gazebo_harmonic_hybird_is_possible.md](./02_px4_autopilot/99_psa_qa/03_px4_cuav_v5_nano_to_gazebo_harmonic_hybird_is_possible.md) : CUAV V5 Nano နှင့် Harmonic ချိတ်ဆက်နိုင်မှု၊ Gemini အဖြေစစ်ဆေးချက်၊ SITL/HITL/SIH နှင့် custom bridge လိုအပ်ချက်
