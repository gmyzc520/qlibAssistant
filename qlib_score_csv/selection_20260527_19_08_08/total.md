# params 
 {'predict_dates': [{'start': '2026-05-27', 'end': '2026-05-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260527_18 590812497311783522 (Recorders: 3/5)

	Recorder: a5557997913f4b759fa3a5f5af7c2c33

		Model: {'id': 'a5557997913f4b759fa3a5f5af7c2c33', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.021, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.140', 'weight': '0.044'}

	Recorder: f39012fdd5644bf08d7ab94a73db5a65

		Model: {'id': 'f39012fdd5644bf08d7ab94a73db5a65', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.018, 'Rank IC': 0.028, 'Rank ICIR': 0.16}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.160', 'weight': '0.050'}

	Recorder: ec52ca6fec8645b5a47796cdd5d9dc63

		Model: {'id': 'ec52ca6fec8645b5a47796cdd5d9dc63', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.259, 'Rank IC': 0.032, 'Rank ICIR': 0.154}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.154', 'weight': '0.048'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260527_18 667980849472409493 (Recorders: 3/5)

	Recorder: 231e80c99fbf4a5db4d9d79032f3f9a8

		Model: {'id': '231e80c99fbf4a5db4d9d79032f3f9a8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.184, 'Rank IC': 0.031, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.236', 'weight': '0.074'}

	Recorder: 06f357d743c74c95ad022042f137e232

		Model: {'id': '06f357d743c74c95ad022042f137e232', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.11, 'Rank IC': 0.011, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-05-27', '2025-11-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.107', 'weight': '0.034'}

	Recorder: 36d9c002328b4e48a891b2db11f4ba3b

		Model: {'id': '36d9c002328b4e48a891b2db11f4ba3b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.482, 'Rank IC': 0.047, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.243', 'weight': '0.076'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260527_16 833538178950568762 (Recorders: 4/5)

	Recorder: 76c69eb874804267839a58470c856554

		Model: {'id': '76c69eb874804267839a58470c856554', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.032, 'Rank ICIR': 0.203}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.203', 'weight': '0.064'}

	Recorder: b5abd7d069124cb681efc264568fa70d

		Model: {'id': 'b5abd7d069124cb681efc264568fa70d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.074, 'Rank IC': 0.041, 'Rank ICIR': 0.224}, 'data_train_vec': ['2022-05-27', '2025-05-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.224', 'weight': '0.070'}

	Recorder: 9e4bc7df98f44ace9b9d7fddd33d5670

		Model: {'id': '9e4bc7df98f44ace9b9d7fddd33d5670', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.194, 'Rank IC': 0.042, 'Rank ICIR': 0.269}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.269', 'weight': '0.084'}

	Recorder: ccc5bea9848148a2a6bdc428a2e5c38f

		Model: {'id': 'ccc5bea9848148a2a6bdc428a2e5c38f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.261, 'Rank IC': 0.017, 'Rank ICIR': 0.091}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.091', 'weight': '0.028'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260527_16 473856161554962781 (Recorders: 3/5)

	Recorder: 70357decab974f77b3a18272159e814f

		Model: {'id': '70357decab974f77b3a18272159e814f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.06, 'Rank IC': 0.034, 'Rank ICIR': 0.292}, 'data_train_vec': ['2021-05-27', '2025-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.292', 'weight': '0.091'}

	Recorder: 74815d00235a494c823c27bceff974f9

		Model: {'id': '74815d00235a494c823c27bceff974f9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.118, 'Rank IC': 0.036, 'Rank ICIR': 0.326}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.326', 'weight': '0.102'}

	Recorder: a062b48b4ad04adb973419aa465b2916

		Model: {'id': 'a062b48b4ad04adb973419aa465b2916', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.092, 'ICIR': 0.507, 'Rank IC': 0.067, 'Rank ICIR': 0.319}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.319', 'weight': '0.100'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260527_16 507898355159878830 (Recorders: 2/5)

	Recorder: 84eb318de11f436d9fd1c5f8766f128b

		Model: {'id': '84eb318de11f436d9fd1c5f8766f128b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.09, 'Rank IC': 0.028, 'Rank ICIR': 0.174}, 'data_train_vec': ['2023-05-27', '2025-08-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.174', 'weight': '0.054'}

	Recorder: 1895157b1dd44cd4a3bcd7398ef8b2d0

		Model: {'id': '1895157b1dd44cd4a3bcd7398ef8b2d0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.314, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27'], 'rank_icir': '0.256', 'weight': '0.080'}
