# params 
 {'predict_dates': [{'start': '2026-05-29', 'end': '2026-05-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260530_16 807230561537791441 (Recorders: 4/5)

	Recorder: f24ab0b16cea4b4dad4eb6de18dee13e

		Model: {'id': 'f24ab0b16cea4b4dad4eb6de18dee13e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.022, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.150', 'weight': '0.054'}

	Recorder: 72b0a144583f4368ab5bc37e32685629

		Model: {'id': '72b0a144583f4368ab5bc37e32685629', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.019, 'Rank ICIR': 0.137}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.137', 'weight': '0.049'}

	Recorder: 42b0e2bed28d40f38bae1389d364fc5e

		Model: {'id': '42b0e2bed28d40f38bae1389d364fc5e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.31, 'Rank IC': 0.029, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.196', 'weight': '0.070'}

	Recorder: 1bd73e6313464085af78dfee24f3a130

		Model: {'id': '1bd73e6313464085af78dfee24f3a130', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.245, 'Rank IC': 0.012, 'Rank ICIR': 0.058}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.058', 'weight': '0.021'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260530_16 751616223428295700 (Recorders: 3/5)

	Recorder: 7acaeafb5a91418898c7f85174b7681a

		Model: {'id': '7acaeafb5a91418898c7f85174b7681a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.16, 'Rank IC': 0.027, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.189', 'weight': '0.068'}

	Recorder: f9758d0959364091a9da2a562fdd1527

		Model: {'id': 'f9758d0959364091a9da2a562fdd1527', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.081, 'Rank IC': 0.009, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: 5770239500c74c38a20bac4f3395b850

		Model: {'id': '5770239500c74c38a20bac4f3395b850', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.34, 'Rank IC': 0.03, 'Rank ICIR': 0.135}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.135', 'weight': '0.048'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260530_14 830347393957869400 (Recorders: 3/5)

	Recorder: 8299833d598b41b6ae74889c9f044b16

		Model: {'id': '8299833d598b41b6ae74889c9f044b16', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.035, 'Rank ICIR': 0.235}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.235', 'weight': '0.084'}

	Recorder: 1956d4a3b9454ffca75421823618daeb

		Model: {'id': '1956d4a3b9454ffca75421823618daeb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.038, 'Rank ICIR': 0.212}, 'data_train_vec': ['2022-05-30', '2025-05-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.212', 'weight': '0.076'}

	Recorder: 617abd8b71dd44cbbb47039c41d5ae45

		Model: {'id': '617abd8b71dd44cbbb47039c41d5ae45', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.23, 'Rank IC': 0.042, 'Rank ICIR': 0.274}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.274', 'weight': '0.098'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260530_14 304054972241861986 (Recorders: 4/5)

	Recorder: fd4387de43394171a60bef2b11b3bf82

		Model: {'id': 'fd4387de43394171a60bef2b11b3bf82', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.035, 'Rank ICIR': 0.304}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.304', 'weight': '0.109'}

	Recorder: 59d1b6d08a3d4cfd8a385268c6914aa2

		Model: {'id': '59d1b6d08a3d4cfd8a385268c6914aa2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.097, 'Rank IC': 0.031, 'Rank ICIR': 0.281}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.281', 'weight': '0.101'}

	Recorder: 93db51dc0ff2441494e27778bfe5a19f

		Model: {'id': '93db51dc0ff2441494e27778bfe5a19f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.011, 'Rank ICIR': 0.083}, 'data_train_vec': ['2024-05-30', '2025-11-29'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.083', 'weight': '0.030'}

	Recorder: 2c3ef1a246294816b14780ad31b24650

		Model: {'id': '2c3ef1a246294816b14780ad31b24650', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.242, 'Rank IC': 0.029, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.124', 'weight': '0.044'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260530_14 389631501877545857 (Recorders: 3/5)

	Recorder: ec8cbb0d93c34027937dc5377ea6a5f0

		Model: {'id': 'ec8cbb0d93c34027937dc5377ea6a5f0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.02, 'Rank ICIR': 0.122}, 'data_train_vec': ['2021-05-28', '2025-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.122', 'weight': '0.044'}

	Recorder: bedd7f73a58c4cc8a15cecd827ecc9c9

		Model: {'id': 'bedd7f73a58c4cc8a15cecd827ecc9c9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.036, 'Rank IC': 0.026, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-05-28', '2025-08-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.168', 'weight': '0.060'}

	Recorder: 8828b610e6644543b2725876f56a533a

		Model: {'id': '8828b610e6644543b2725876f56a533a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.086, 'Rank IC': 0.006, 'Rank ICIR': 0.037}, 'data_train_vec': ['2025-05-28', '2026-02-27'], 'train_time_vec': ['2026-05-30', '2026-05-30'], 'rank_icir': '0.037', 'weight': '0.013'}
