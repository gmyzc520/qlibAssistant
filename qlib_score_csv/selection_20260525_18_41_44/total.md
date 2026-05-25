# params 
 {'predict_dates': [{'start': '2026-05-25', 'end': '2026-05-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260525_18 288667133305311957 (Recorders: 3/5)

	Recorder: eb2c7a21173e4be4a93d9aeafc5e88ed

		Model: {'id': 'eb2c7a21173e4be4a93d9aeafc5e88ed', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.076, 'Rank IC': 0.031, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.220', 'weight': '0.057'}

	Recorder: 7ecf0a5293f244bf8d6c2d7d2af6fcf9

		Model: {'id': '7ecf0a5293f244bf8d6c2d7d2af6fcf9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.237, 'Rank IC': 0.034, 'Rank ICIR': 0.24}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.240', 'weight': '0.062'}

	Recorder: 9d84c5399d604820af41c594e73ee3da

		Model: {'id': '9d84c5399d604820af41c594e73ee3da', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.071, 'ICIR': 0.363, 'Rank IC': 0.05, 'Rank ICIR': 0.29}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.290', 'weight': '0.075'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260525_18 473160621341545985 (Recorders: 3/5)

	Recorder: 706cac07e9824b028db32aff3941fe6e

		Model: {'id': '706cac07e9824b028db32aff3941fe6e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.022, 'Rank ICIR': 0.17}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.170', 'weight': '0.044'}

	Recorder: 979a131ba2504def9431af2a4272e389

		Model: {'id': '979a131ba2504def9431af2a4272e389', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.173, 'Rank IC': 0.005, 'Rank ICIR': 0.041}, 'data_train_vec': ['2024-05-25', '2025-11-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.041', 'weight': '0.011'}

	Recorder: ac7b67eb988e435aa60c0d25d19a589f

		Model: {'id': 'ac7b67eb988e435aa60c0d25d19a589f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.536, 'Rank IC': 0.052, 'Rank ICIR': 0.273}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.273', 'weight': '0.070'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260525_15 867219297114138079 (Recorders: 4/5)

	Recorder: 87440dfec6114430a2cb49d201f180b2

		Model: {'id': '87440dfec6114430a2cb49d201f180b2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.079, 'Rank IC': 0.033, 'Rank ICIR': 0.224}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.224', 'weight': '0.058'}

	Recorder: 28c0c9eaa2e7444cad012bc616c18292

		Model: {'id': '28c0c9eaa2e7444cad012bc616c18292', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.05, 'Rank IC': 0.037, 'Rank ICIR': 0.206}, 'data_train_vec': ['2022-05-25', '2025-05-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.206', 'weight': '0.053'}

	Recorder: 455e266aa1544bfc838d0ba193a2d79d

		Model: {'id': '455e266aa1544bfc838d0ba193a2d79d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.177, 'Rank IC': 0.04, 'Rank ICIR': 0.267}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.267', 'weight': '0.069'}

	Recorder: 6d4c07b0e8674e6080690bb2473f0dee

		Model: {'id': '6d4c07b0e8674e6080690bb2473f0dee', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.441, 'Rank IC': 0.059, 'Rank ICIR': 0.311}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.311', 'weight': '0.080'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260525_15 520080459848999787 (Recorders: 4/5)

	Recorder: d72bb24209354b9a9a7ea3242843ba8d

		Model: {'id': 'd72bb24209354b9a9a7ea3242843ba8d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.031, 'Rank ICIR': 0.277}, 'data_train_vec': ['2021-05-25', '2025-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.277', 'weight': '0.071'}

	Recorder: 97d6a682cf0142849727448c2353b16e

		Model: {'id': '97d6a682cf0142849727448c2353b16e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.094, 'Rank IC': 0.036, 'Rank ICIR': 0.329}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.329', 'weight': '0.085'}

	Recorder: 3b76d19853984fd283ea76d7fa70766b

		Model: {'id': '3b76d19853984fd283ea76d7fa70766b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.01, 'Rank ICIR': 0.079}, 'data_train_vec': ['2024-05-25', '2025-11-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.079', 'weight': '0.020'}

	Recorder: fdd3a62fda184f699e83d942e7cb168b

		Model: {'id': 'fdd3a62fda184f699e83d942e7cb168b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.11, 'ICIR': 0.624, 'Rank IC': 0.089, 'Rank ICIR': 0.45}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.450', 'weight': '0.116'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260525_15 832181393599088246 (Recorders: 2/5)

	Recorder: 7ee0bec6bc1a45059f7da14067f8305a

		Model: {'id': '7ee0bec6bc1a45059f7da14067f8305a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.13, 'Rank IC': 0.034, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-05-25', '2025-08-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.215', 'weight': '0.055'}

	Recorder: 68bf6f20127942a79e4b58a718e5e6e2

		Model: {'id': '68bf6f20127942a79e4b58a718e5e6e2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.32, 'Rank IC': 0.042, 'Rank ICIR': 0.295}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25'], 'rank_icir': '0.295', 'weight': '0.076'}
