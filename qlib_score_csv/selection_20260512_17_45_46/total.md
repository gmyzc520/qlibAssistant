# params 
 {'predict_dates': [{'start': '2026-05-12', 'end': '2026-05-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260512_17 687866176076007560 (Recorders: 4/5)

	Recorder: 4e6d9e8e1d2d4f089610ecaf8895b375

		Model: {'id': '4e6d9e8e1d2d4f089610ecaf8895b375', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.094, 'Rank IC': 0.013, 'Rank ICIR': 0.081}, 'data_train_vec': ['2022-05-12', '2025-05-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.081', 'weight': '0.030'}

	Recorder: 6b2fd7ed11ff4b4f81236515a21a28b4

		Model: {'id': '6b2fd7ed11ff4b4f81236515a21a28b4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.107, 'Rank IC': 0.02, 'Rank ICIR': 0.136}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.136', 'weight': '0.050'}

	Recorder: 4a1c7b9e17aa4ba880f571350af48d17

		Model: {'id': '4a1c7b9e17aa4ba880f571350af48d17', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.087, 'Rank IC': 0.016, 'Rank ICIR': 0.135}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.135', 'weight': '0.049'}

	Recorder: b51b1cfd54fa4b8d900868c2dca8eae2

		Model: {'id': 'b51b1cfd54fa4b8d900868c2dca8eae2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.42, 'Rank IC': 0.018, 'Rank ICIR': 0.145}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.145', 'weight': '0.053'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260512_17 150106527768860547 (Recorders: 3/5)

	Recorder: d2e8711fcefc4455afd83237151bbedb

		Model: {'id': 'd2e8711fcefc4455afd83237151bbedb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.079, 'Rank IC': 0.018, 'Rank ICIR': 0.159}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.159', 'weight': '0.058'}

	Recorder: b85d64531ec94a9f8f368c7c319ac9b9

		Model: {'id': 'b85d64531ec94a9f8f368c7c319ac9b9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.146, 'Rank IC': 0.013, 'Rank ICIR': 0.108}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.108', 'weight': '0.039'}

	Recorder: 38df524537d2454c8508ad50ba627315

		Model: {'id': '38df524537d2454c8508ad50ba627315', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.586, 'Rank IC': 0.024, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.217', 'weight': '0.079'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260512_14 269902382255516923 (Recorders: 3/5)

	Recorder: 7f8f23acb17a4f6a8eba6e261b41e2f8

		Model: {'id': '7f8f23acb17a4f6a8eba6e261b41e2f8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.07, 'Rank IC': 0.027, 'Rank ICIR': 0.182}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.182', 'weight': '0.066'}

	Recorder: 44f5119df77d44ff9ac4e19997968bdc

		Model: {'id': '44f5119df77d44ff9ac4e19997968bdc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.004, 'Rank ICIR': 0.031}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.031', 'weight': '0.011'}

	Recorder: 0426dcb1d2b0429fb29e1c0c2f5df037

		Model: {'id': '0426dcb1d2b0429fb29e1c0c2f5df037', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.547, 'Rank IC': 0.022, 'Rank ICIR': 0.198}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.198', 'weight': '0.072'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260512_14 114060602572728292 (Recorders: 4/5)

	Recorder: 6e0cb152f78746748ca8a1c949741544

		Model: {'id': '6e0cb152f78746748ca8a1c949741544', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.02, 'Rank ICIR': 0.188}, 'data_train_vec': ['2021-05-12', '2025-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.188', 'weight': '0.069'}

	Recorder: 8c5ae4c9feec4796b8f38d6775a7a942

		Model: {'id': '8c5ae4c9feec4796b8f38d6775a7a942', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.225', 'weight': '0.082'}

	Recorder: 5646fbc0dd8d4c7fa5684e577d779074

		Model: {'id': '5646fbc0dd8d4c7fa5684e577d779074', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.08, 'Rank IC': 0.019, 'Rank ICIR': 0.164}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.164', 'weight': '0.060'}

	Recorder: 74f04e7787af461b83137f2b185eaba5

		Model: {'id': '74f04e7787af461b83137f2b185eaba5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.622, 'Rank IC': 0.021, 'Rank ICIR': 0.247}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.247', 'weight': '0.090'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260512_14 145229668690942629 (Recorders: 4/5)

	Recorder: d4ebe810667c4045a9097b72c03fb298

		Model: {'id': 'd4ebe810667c4045a9097b72c03fb298', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.011, 'Rank ICIR': 0.063}, 'data_train_vec': ['2022-05-12', '2025-05-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.063', 'weight': '0.023'}

	Recorder: 033d8a785ac44de9b5e6e3b6b8056e55

		Model: {'id': '033d8a785ac44de9b5e6e3b6b8056e55', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.086, 'Rank IC': 0.024, 'Rank ICIR': 0.14}, 'data_train_vec': ['2023-05-12', '2025-08-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.140', 'weight': '0.051'}

	Recorder: 7fb383d45bf2448984af11bfd7cf7e3f

		Model: {'id': '7fb383d45bf2448984af11bfd7cf7e3f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.071, 'Rank IC': 0.008, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-05-12', '2025-11-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.061', 'weight': '0.022'}

	Recorder: 4499fed4dbab42f9a1b32ca4282734c6

		Model: {'id': '4499fed4dbab42f9a1b32ca4282734c6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.422, 'Rank IC': 0.019, 'Rank ICIR': 0.259}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12'], 'rank_icir': '0.259', 'weight': '0.095'}
