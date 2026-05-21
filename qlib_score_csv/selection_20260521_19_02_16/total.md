# params 
 {'predict_dates': [{'start': '2026-05-21', 'end': '2026-05-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260521_18 956910274058195638 (Recorders: 3/5)

	Recorder: 45d54012168440d398441b02bd49e8e2

		Model: {'id': '45d54012168440d398441b02bd49e8e2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2022-05-21', '2025-05-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.133', 'weight': '0.049'}

	Recorder: a49c3a9eb16049e4ad38ede961a5a4c0

		Model: {'id': 'a49c3a9eb16049e4ad38ede961a5a4c0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.077, 'Rank IC': 0.024, 'Rank ICIR': 0.141}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.141', 'weight': '0.052'}

	Recorder: bad851cd2d6a4c8c947979a33024e295

		Model: {'id': 'bad851cd2d6a4c8c947979a33024e295', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.256, 'Rank IC': 0.014, 'Rank ICIR': 0.088}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.088', 'weight': '0.032'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260521_18 699034593760179369 (Recorders: 3/5)

	Recorder: 74f7e0be47ea43279d614e40d1a391ab

		Model: {'id': '74f7e0be47ea43279d614e40d1a391ab', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.081, 'Rank IC': 0.02, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.156', 'weight': '0.057'}

	Recorder: 3f88f344925b4bd4a796bb1f4770521b

		Model: {'id': '3f88f344925b4bd4a796bb1f4770521b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.194, 'Rank IC': 0.01, 'Rank ICIR': 0.097}, 'data_train_vec': ['2024-05-21', '2025-11-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.097', 'weight': '0.035'}

	Recorder: 03a2a379744b4579b0f291e49956f6df

		Model: {'id': '03a2a379744b4579b0f291e49956f6df', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.378, 'Rank IC': 0.022, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.117', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260521_16 805228532518686473 (Recorders: 4/5)

	Recorder: a9b45c2ef1f241649680af1d35f974d5

		Model: {'id': 'a9b45c2ef1f241649680af1d35f974d5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.03, 'Rank IC': 0.028, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-05-21', '2025-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.178', 'weight': '0.065'}

	Recorder: 2fcea84c08a442a3ab64e414f50e10e3

		Model: {'id': '2fcea84c08a442a3ab64e414f50e10e3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.047, 'Rank IC': 0.037, 'Rank ICIR': 0.213}, 'data_train_vec': ['2022-05-21', '2025-05-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.213', 'weight': '0.078'}

	Recorder: 6c7be937aa7040479e2211102695e657

		Model: {'id': '6c7be937aa7040479e2211102695e657', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.149, 'Rank IC': 0.038, 'Rank ICIR': 0.259}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.259', 'weight': '0.095'}

	Recorder: 9a7904693a6c454d87fba758511b42d8

		Model: {'id': '9a7904693a6c454d87fba758511b42d8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.303, 'Rank IC': 0.018, 'Rank ICIR': 0.098}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.098', 'weight': '0.036'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260521_15 612245325871466263 (Recorders: 3/5)

	Recorder: d1a518bbb39c4c3292e21c8e4b604b95

		Model: {'id': 'd1a518bbb39c4c3292e21c8e4b604b95', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.06, 'Rank IC': 0.029, 'Rank ICIR': 0.264}, 'data_train_vec': ['2021-05-21', '2025-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.264', 'weight': '0.097'}

	Recorder: e0e0fe7aefed4ad8a1b89f561b844988

		Model: {'id': 'e0e0fe7aefed4ad8a1b89f561b844988', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.074, 'Rank IC': 0.033, 'Rank ICIR': 0.314}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.314', 'weight': '0.115'}

	Recorder: 086d4831a85d419b8af31cf730f609c9

		Model: {'id': '086d4831a85d419b8af31cf730f609c9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.457, 'Rank IC': 0.044, 'Rank ICIR': 0.253}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.253', 'weight': '0.093'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260521_15 493850187888364451 (Recorders: 2/5)

	Recorder: b3556d9a05d74cc3ad6456f4d1f3126e

		Model: {'id': 'b3556d9a05d74cc3ad6456f4d1f3126e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.095, 'Rank IC': 0.032, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-05-21', '2025-08-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.222', 'weight': '0.081'}

	Recorder: 0a8bf20426f746fa87e47295471dc841

		Model: {'id': '0a8bf20426f746fa87e47295471dc841', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.307, 'Rank IC': 0.028, 'Rank ICIR': 0.201}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21'], 'rank_icir': '0.201', 'weight': '0.074'}
