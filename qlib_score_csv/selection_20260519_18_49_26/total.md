# params 
 {'predict_dates': [{'start': '2026-05-19', 'end': '2026-05-19'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260519_18 442752214402231499 (Recorders: 4/5)

	Recorder: 0035978bbdc44a738dd0774360e2af7b

		Model: {'id': '0035978bbdc44a738dd0774360e2af7b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.085, 'Rank IC': 0.022, 'Rank ICIR': 0.143}, 'data_train_vec': ['2022-05-19', '2025-05-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.143', 'weight': '0.043'}

	Recorder: a8b5f94e2ca0420db6d93c029ae60976

		Model: {'id': 'a8b5f94e2ca0420db6d93c029ae60976', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.032, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.196', 'weight': '0.059'}

	Recorder: b642ace3dfe54aa9940c51465a4d8ad8

		Model: {'id': 'b642ace3dfe54aa9940c51465a4d8ad8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.142, 'Rank IC': 0.01, 'Rank ICIR': 0.092}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.092', 'weight': '0.028'}

	Recorder: 6bc2119278cf4ad0950370b20f75981f

		Model: {'id': '6bc2119278cf4ad0950370b20f75981f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.258, 'Rank IC': 0.037, 'Rank ICIR': 0.227}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.227', 'weight': '0.068'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260519_18 471886327583510659 (Recorders: 3/5)

	Recorder: f60df0eefcb742eca95f9049ff4f8a15

		Model: {'id': 'f60df0eefcb742eca95f9049ff4f8a15', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.164, 'Rank IC': 0.029, 'Rank ICIR': 0.243}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.243', 'weight': '0.073'}

	Recorder: 7278a8efdf2243c881f049f2b46de42f

		Model: {'id': '7278a8efdf2243c881f049f2b46de42f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.133, 'Rank IC': 0.005, 'Rank ICIR': 0.05}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.050', 'weight': '0.015'}

	Recorder: c3971fbd67184ec48cd63cedfd7ced5e

		Model: {'id': 'c3971fbd67184ec48cd63cedfd7ced5e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.577, 'Rank IC': 0.043, 'Rank ICIR': 0.257}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.257', 'weight': '0.077'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260519_15 180627041166905000 (Recorders: 4/5)

	Recorder: 491014f444e34d238dba962805df9db4

		Model: {'id': '491014f444e34d238dba962805df9db4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.023, 'Rank IC': 0.027, 'Rank ICIR': 0.169}, 'data_train_vec': ['2021-05-19', '2025-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.169', 'weight': '0.051'}

	Recorder: dab809d9c5a648b0a8f659dfd01c6af7

		Model: {'id': 'dab809d9c5a648b0a8f659dfd01c6af7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.03, 'Rank ICIR': 0.169}, 'data_train_vec': ['2022-05-19', '2025-05-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.169', 'weight': '0.051'}

	Recorder: e04c9fcb678a49c28cb9fcb38da4eff7

		Model: {'id': 'e04c9fcb678a49c28cb9fcb38da4eff7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.128, 'Rank IC': 0.038, 'Rank ICIR': 0.243}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.243', 'weight': '0.073'}

	Recorder: 699c999730254f81a96fa2d56fd18281

		Model: {'id': '699c999730254f81a96fa2d56fd18281', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.065, 'ICIR': 0.378, 'Rank IC': 0.032, 'Rank ICIR': 0.177}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.177', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260519_15 609196378370965969 (Recorders: 4/5)

	Recorder: ee7e8fbaf0974ef8937330ed5351e2be

		Model: {'id': 'ee7e8fbaf0974ef8937330ed5351e2be', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.031, 'Rank ICIR': 0.276}, 'data_train_vec': ['2021-05-19', '2025-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.276', 'weight': '0.083'}

	Recorder: dd70fe95cbcc49979825778b78cd4677

		Model: {'id': 'dd70fe95cbcc49979825778b78cd4677', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.091, 'Rank IC': 0.036, 'Rank ICIR': 0.325}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.325', 'weight': '0.098'}

	Recorder: 86f7dc09bf6e4a0aaf85612cf84a155f

		Model: {'id': '86f7dc09bf6e4a0aaf85612cf84a155f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.044, 'Rank IC': 0.014, 'Rank ICIR': 0.123}, 'data_train_vec': ['2024-05-19', '2025-11-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.123', 'weight': '0.037'}

	Recorder: 3aee3b5fb9d44d4c8db33ad1f579be47

		Model: {'id': '3aee3b5fb9d44d4c8db33ad1f579be47', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.071, 'ICIR': 0.513, 'Rank IC': 0.048, 'Rank ICIR': 0.3}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.300', 'weight': '0.090'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260519_15 571072592865424865 (Recorders: 2/5)

	Recorder: e328bccdfaff4e1093ad3b33b5dc6ed7

		Model: {'id': 'e328bccdfaff4e1093ad3b33b5dc6ed7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2023-05-19', '2025-08-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.148', 'weight': '0.044'}

	Recorder: 9957b559351d4c1f93212a6c32a03282

		Model: {'id': '9957b559351d4c1f93212a6c32a03282', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.235, 'Rank IC': 0.031, 'Rank ICIR': 0.193}, 'data_train_vec': ['2025-05-19', '2026-02-18'], 'train_time_vec': ['2026-05-19', '2026-05-19'], 'rank_icir': '0.193', 'weight': '0.058'}
