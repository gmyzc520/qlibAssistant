# params 
 {'predict_dates': [{'start': '2026-05-14', 'end': '2026-05-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260514_17 423202847206499478 (Recorders: 3/5)

	Recorder: 0daffe0fa96b4bafac0f8ca0f9480221

		Model: {'id': '0daffe0fa96b4bafac0f8ca0f9480221', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.053, 'Rank IC': 0.021, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-05-14', '2025-05-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.138', 'weight': '0.055'}

	Recorder: da54cf89c4d6445c83992e48083c9741

		Model: {'id': 'da54cf89c4d6445c83992e48083c9741', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.138, 'Rank IC': 0.011, 'Rank ICIR': 0.075}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.075', 'weight': '0.030'}

	Recorder: 867385b4a5e24c6d8db7773d9e8326b4

		Model: {'id': '867385b4a5e24c6d8db7773d9e8326b4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.473, 'Rank IC': 0.037, 'Rank ICIR': 0.229}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.229', 'weight': '0.091'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260514_17 412455482069799490 (Recorders: 3/5)

	Recorder: b913a3a0786b450ea33b006a941632d1

		Model: {'id': 'b913a3a0786b450ea33b006a941632d1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.19, 'Rank IC': 0.027, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.225', 'weight': '0.090'}

	Recorder: c425cec1c0c74b5e8620a010f4ec9d90

		Model: {'id': 'c425cec1c0c74b5e8620a010f4ec9d90', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.127, 'Rank IC': 0.006, 'Rank ICIR': 0.057}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.057', 'weight': '0.023'}

	Recorder: eec1b8cb08094ce79000161004a5a110

		Model: {'id': 'eec1b8cb08094ce79000161004a5a110', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.639, 'Rank IC': 0.046, 'Rank ICIR': 0.304}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.304', 'weight': '0.121'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260514_14 522505893134017095 (Recorders: 3/5)

	Recorder: 86663e8995734d7ab30258d9706a3bdf

		Model: {'id': '86663e8995734d7ab30258d9706a3bdf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.032, 'Rank ICIR': 0.17}, 'data_train_vec': ['2022-05-14', '2025-05-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.170', 'weight': '0.068'}

	Recorder: f7185def169043cbb4956679f75d942b

		Model: {'id': 'f7185def169043cbb4956679f75d942b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.119, 'Rank IC': 0.035, 'Rank ICIR': 0.231}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.231', 'weight': '0.092'}

	Recorder: 226eadd818f04e288857e41e5d5262cb

		Model: {'id': '226eadd818f04e288857e41e5d5262cb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.083, 'ICIR': 0.494, 'Rank IC': 0.037, 'Rank ICIR': 0.206}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.206', 'weight': '0.082'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260514_14 248275204026162611 (Recorders: 3/5)

	Recorder: 0b5133e3c491493da5ebc35cbf351668

		Model: {'id': '0b5133e3c491493da5ebc35cbf351668', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.021, 'Rank IC': 0.027, 'Rank ICIR': 0.246}, 'data_train_vec': ['2023-05-14', '2025-08-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.246', 'weight': '0.098'}

	Recorder: 8891fe91de8f4874b6897a075d7f0570

		Model: {'id': '8891fe91de8f4874b6897a075d7f0570', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.076, 'Rank IC': 0.019, 'Rank ICIR': 0.166}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.166', 'weight': '0.066'}

	Recorder: 05b3e0f0aab9483b9d1777876a923413

		Model: {'id': '05b3e0f0aab9483b9d1777876a923413', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.528, 'Rank IC': 0.044, 'Rank ICIR': 0.277}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.277', 'weight': '0.110'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260514_14 474511609387831097 (Recorders: 2/5)

	Recorder: 692e5232421c44f8a253ddab3ef09d90

		Model: {'id': '692e5232421c44f8a253ddab3ef09d90', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.121, 'Rank IC': 0.002, 'Rank ICIR': 0.018}, 'data_train_vec': ['2024-05-14', '2025-11-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.018', 'weight': '0.007'}

	Recorder: 2798d6f2f09d464ba6e169fa0c19a1db

		Model: {'id': '2798d6f2f09d464ba6e169fa0c19a1db', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.489, 'Rank IC': 0.025, 'Rank ICIR': 0.171}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14'], 'rank_icir': '0.171', 'weight': '0.068'}
