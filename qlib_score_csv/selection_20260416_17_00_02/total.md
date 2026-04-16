# params 
 {'predict_dates': [{'start': '2026-04-16', 'end': '2026-04-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260416_16 101664125444121391 (Recorders: 3/5)

	Recorder: a090b7c6798b413187c18ad0d9d0e3c6

		Model: {'id': 'a090b7c6798b413187c18ad0d9d0e3c6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.259, 'Rank IC': 0.045, 'Rank ICIR': 0.305}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.305', 'weight': '0.084'}

	Recorder: 511e24c73ecd4497b798567be9389403

		Model: {'id': '511e24c73ecd4497b798567be9389403', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.33, 'Rank IC': 0.056, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.391', 'weight': '0.107'}

	Recorder: db0538127c954dc5a5f24e49bc951a6e

		Model: {'id': 'db0538127c954dc5a5f24e49bc951a6e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.37, 'Rank IC': 0.048, 'Rank ICIR': 0.292}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.292', 'weight': '0.080'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260416_16 107770838393922960 (Recorders: 2/5)

	Recorder: 52eef678d31d418389c6fcc8cd36d35a

		Model: {'id': '52eef678d31d418389c6fcc8cd36d35a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.125, 'Rank IC': 0.029, 'Rank ICIR': 0.239}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.239', 'weight': '0.066'}

	Recorder: 56e1759321804290bd58a7506bb26c91

		Model: {'id': '56e1759321804290bd58a7506bb26c91', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.305, 'Rank IC': 0.037, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.245', 'weight': '0.067'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260416_14 889622997563022399 (Recorders: 4/5)

	Recorder: 8116dfdf3a204b62b22909c7973341eb

		Model: {'id': '8116dfdf3a204b62b22909c7973341eb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.038, 'Rank IC': 0.025, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.148', 'weight': '0.041'}

	Recorder: dfb5b24141d44986b2110926252974bc

		Model: {'id': 'dfb5b24141d44986b2110926252974bc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.102, 'Rank IC': 0.046, 'Rank ICIR': 0.266}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.266', 'weight': '0.073'}

	Recorder: cfbef22b54984e03ab14a2d36a723f05

		Model: {'id': 'cfbef22b54984e03ab14a2d36a723f05', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.137, 'Rank IC': 0.025, 'Rank ICIR': 0.184}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.184', 'weight': '0.050'}

	Recorder: f25563ae1a604b70b81df60e035d7c1c

		Model: {'id': 'f25563ae1a604b70b81df60e035d7c1c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.247, 'Rank IC': 0.033, 'Rank ICIR': 0.188}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.188', 'weight': '0.052'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260416_14 773742827722461767 (Recorders: 4/5)

	Recorder: e8b2f6bc2d8f482c8c747b2ed8c34654

		Model: {'id': 'e8b2f6bc2d8f482c8c747b2ed8c34654', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.016, 'Rank ICIR': 0.136}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.136', 'weight': '0.037'}

	Recorder: f4601c56cd064d00ac392de8f602df75

		Model: {'id': 'f4601c56cd064d00ac392de8f602df75', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.033, 'Rank IC': 0.029, 'Rank ICIR': 0.242}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.242', 'weight': '0.066'}

	Recorder: 65c3eda214194c38a1e0fa3e9ba20be5

		Model: {'id': '65c3eda214194c38a1e0fa3e9ba20be5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.076, 'Rank IC': 0.017, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-04-16', '2025-10-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.142', 'weight': '0.039'}

	Recorder: 41029b941787479ca9c367fad471b71b

		Model: {'id': '41029b941787479ca9c367fad471b71b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.06, 'ICIR': 0.354, 'Rank IC': 0.047, 'Rank ICIR': 0.265}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.265', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260416_14 325827260039287961 (Recorders: 3/5)

	Recorder: 3766329ed8f44723adb5d47b7dfde0d8

		Model: {'id': '3766329ed8f44723adb5d47b7dfde0d8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.094, 'Rank IC': 0.021, 'Rank ICIR': 0.116}, 'data_train_vec': ['2021-04-16', '2025-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.116', 'weight': '0.032'}

	Recorder: 3d207f0470434a0ea198e97309fbfd7f

		Model: {'id': '3d207f0470434a0ea198e97309fbfd7f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.102, 'Rank IC': 0.04, 'Rank ICIR': 0.241}, 'data_train_vec': ['2023-04-16', '2025-07-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.241', 'weight': '0.066'}

	Recorder: b9951081c2654868911f4dce1e36489d

		Model: {'id': 'b9951081c2654868911f4dce1e36489d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.26, 'Rank IC': 0.035, 'Rank ICIR': 0.244}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16'], 'rank_icir': '0.244', 'weight': '0.067'}
