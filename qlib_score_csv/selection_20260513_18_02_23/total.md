# params 
 {'predict_dates': [{'start': '2026-05-13', 'end': '2026-05-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260513_17 985561444706220044 (Recorders: 2/5)

	Recorder: 2dfc3dc007144e5c93adc407ec3e75f2

		Model: {'id': '2dfc3dc007144e5c93adc407ec3e75f2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.02, 'Rank IC': 0.004, 'Rank ICIR': 0.032}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.032', 'weight': '0.013'}

	Recorder: dc702cd01cdc4e4989e27aaacb043cac

		Model: {'id': 'dc702cd01cdc4e4989e27aaacb043cac', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.085, 'ICIR': 0.779, 'Rank IC': 0.047, 'Rank ICIR': 0.425}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.425', 'weight': '0.169'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260513_17 548652287139725579 (Recorders: 3/5)

	Recorder: d0891427a38644de9013f40e0e4e39ea

		Model: {'id': 'd0891427a38644de9013f40e0e4e39ea', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.179, 'Rank IC': 0.024, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.206', 'weight': '0.082'}

	Recorder: 24844fad1b2c428dab9653c1fa2dae12

		Model: {'id': '24844fad1b2c428dab9653c1fa2dae12', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.197, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.025', 'weight': '0.010'}

	Recorder: 593ee1c2b0ce4853b12d270567cf9bf3

		Model: {'id': '593ee1c2b0ce4853b12d270567cf9bf3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.097, 'ICIR': 0.678, 'Rank IC': 0.045, 'Rank ICIR': 0.325}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.325', 'weight': '0.130'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260513_15 919289490887471895 (Recorders: 2/5)

	Recorder: 1bdf248e1e03492c8a048d8624e96603

		Model: {'id': '1bdf248e1e03492c8a048d8624e96603', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.087, 'Rank IC': 0.03, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.196', 'weight': '0.078'}

	Recorder: 468f482120844b6a828d0de0e179ac40

		Model: {'id': '468f482120844b6a828d0de0e179ac40', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.079, 'ICIR': 0.64, 'Rank IC': 0.035, 'Rank ICIR': 0.28}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.280', 'weight': '0.112'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260513_15 145863984536768995 (Recorders: 3/5)

	Recorder: 48b9866759634163a3d810058e2700d4

		Model: {'id': '48b9866759634163a3d810058e2700d4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.234}, 'data_train_vec': ['2023-05-13', '2025-08-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.234', 'weight': '0.093'}

	Recorder: 2cf25d353f4c4a9a98ccfdba78e88f6e

		Model: {'id': '2cf25d353f4c4a9a98ccfdba78e88f6e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.124, 'Rank IC': 0.024, 'Rank ICIR': 0.21}, 'data_train_vec': ['2024-05-13', '2025-11-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.210', 'weight': '0.084'}

	Recorder: b50e2d382efb4561b51ede4b0221f4a4

		Model: {'id': 'b50e2d382efb4561b51ede4b0221f4a4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.608, 'Rank IC': 0.045, 'Rank ICIR': 0.366}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.366', 'weight': '0.146'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260513_14 131894613443549475 (Recorders: 1/5)

	Recorder: 640737c9f4274a64bee07520fec12126

		Model: {'id': '640737c9f4274a64bee07520fec12126', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.407, 'Rank IC': 0.022, 'Rank ICIR': 0.209}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13'], 'rank_icir': '0.209', 'weight': '0.083'}
