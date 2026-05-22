# params 
 {'predict_dates': [{'start': '2026-05-22', 'end': '2026-05-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260522_18 596209291941297581 (Recorders: 3/5)

	Recorder: 52e902da8bc54d108f4c3f4caeb3b4b9

		Model: {'id': '52e902da8bc54d108f4c3f4caeb3b4b9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.03, 'Rank IC': 0.027, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-05-22', '2025-05-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.189', 'weight': '0.055'}

	Recorder: 0af22b137e9a4c378873c9b91b79a066

		Model: {'id': '0af22b137e9a4c378873c9b91b79a066', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.119, 'Rank IC': 0.037, 'Rank ICIR': 0.254}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.254', 'weight': '0.074'}

	Recorder: ac4160258cb64f62b94c7f662b2922b1

		Model: {'id': 'ac4160258cb64f62b94c7f662b2922b1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.48, 'Rank IC': 0.03, 'Rank ICIR': 0.182}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.182', 'weight': '0.053'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260522_17 965182439707847509 (Recorders: 3/5)

	Recorder: fe8d893e618a487b859e51481b5b19dc

		Model: {'id': 'fe8d893e618a487b859e51481b5b19dc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.182, 'Rank IC': 0.027, 'Rank ICIR': 0.219}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.219', 'weight': '0.064'}

	Recorder: 6b78fd3c365448e1941fbb0d20d7de92

		Model: {'id': '6b78fd3c365448e1941fbb0d20d7de92', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.228, 'Rank IC': 0.007, 'Rank ICIR': 0.07}, 'data_train_vec': ['2024-05-22', '2025-11-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.070', 'weight': '0.020'}

	Recorder: fba7eb0faef047cab13c4839b0882406

		Model: {'id': 'fba7eb0faef047cab13c4839b0882406', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.096, 'ICIR': 0.536, 'Rank IC': 0.047, 'Rank ICIR': 0.252}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.252', 'weight': '0.073'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260522_15 453966404543242944 (Recorders: 4/5)

	Recorder: 30317284c118464c90dfed2f6c69078b

		Model: {'id': '30317284c118464c90dfed2f6c69078b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.029, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-05-22', '2025-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.194', 'weight': '0.056'}

	Recorder: 7e284177ec57431b8bd3b3c54f9c72b5

		Model: {'id': '7e284177ec57431b8bd3b3c54f9c72b5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.035, 'Rank IC': 0.038, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-05-22', '2025-05-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.216', 'weight': '0.063'}

	Recorder: a3812f92761d4df694f4e11788c0ad07

		Model: {'id': 'a3812f92761d4df694f4e11788c0ad07', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.163, 'Rank IC': 0.038, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.258', 'weight': '0.075'}

	Recorder: 26a7cdfc0ce241a1bc2ada811ad377dd

		Model: {'id': '26a7cdfc0ce241a1bc2ada811ad377dd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.425, 'Rank IC': 0.039, 'Rank ICIR': 0.213}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.213', 'weight': '0.062'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260522_15 382060447425611853 (Recorders: 4/5)

	Recorder: b8ff7021efcf4bd8a3c4acfcb23dcf93

		Model: {'id': 'b8ff7021efcf4bd8a3c4acfcb23dcf93', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.065, 'Rank IC': 0.031, 'Rank ICIR': 0.28}, 'data_train_vec': ['2021-05-22', '2025-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.280', 'weight': '0.082'}

	Recorder: f260b8cd13f54f608fb1d8a8a392995b

		Model: {'id': 'f260b8cd13f54f608fb1d8a8a392995b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.108, 'Rank IC': 0.036, 'Rank ICIR': 0.337}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.337', 'weight': '0.098'}

	Recorder: 01e585c2bd394741818b183cc881f4f5

		Model: {'id': '01e585c2bd394741818b183cc881f4f5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.012, 'Rank ICIR': 0.091}, 'data_train_vec': ['2024-05-22', '2025-11-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.091', 'weight': '0.026'}

	Recorder: dd80fe12711f4f1e995ec5bf34103604

		Model: {'id': 'dd80fe12711f4f1e995ec5bf34103604', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.486, 'Rank IC': 0.059, 'Rank ICIR': 0.311}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.311', 'weight': '0.091'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260522_15 229061447679798423 (Recorders: 2/5)

	Recorder: 59d065d1f5194b0fbc64f2a09c3effbb

		Model: {'id': '59d065d1f5194b0fbc64f2a09c3effbb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.075, 'Rank IC': 0.032, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-05-22', '2025-08-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.233', 'weight': '0.068'}

	Recorder: 6a3081cdaba3486ab3c89585e47e5148

		Model: {'id': '6a3081cdaba3486ab3c89585e47e5148', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.349, 'Rank IC': 0.021, 'Rank ICIR': 0.135}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22'], 'rank_icir': '0.135', 'weight': '0.039'}
